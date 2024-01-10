<template>
    <aside class="flex justify-between px-3 py-3 md:hidden">
        <img @click="handleOpen" class="cursor-pointer" src="/hamburguer.png" alt="" />
        <div class="flex items-center gap-x-8">
            <div class="flex gap-x-4">
                <img src="/search.png" alt="" />
                <img src="/bell.png" alt="" />
            </div>
            <div class="flex items-center gap-x-2">
                <img src="/userphoto.png" alt="" />
            </div>
        </div>
    </aside>
    <div
        @click="handleOpen"
        v-if="isOpen === true"
        class="bg-black/20 w-screen h-screen absolute"
    ></div>
    <div
        v-if="isOpen === true"
        class="absolute bg-white flex flex-col items-center justify-center w-4/5 h-full"
    >
        <img
            @click="handleOpen"
            class="cursor-pointer absolute top-0 right-0 p-6"
            src="/hamburguer.png"
            alt=""
        />

        <h1 class="text-[#272727] text-3xl font-semibold">
            <span class="text-[#9E6EFE]">e</span>Front
        </h1>
        <ol class="flex flex-col gap-y-6">
            <span>
                <li class="text-[#9E6EFE] bg-[#e8e0f7]/30 rounded-md py-2 px-3 flex gap-x-4">
                    <img src="/dashboard.png" alt="" />
                    Dashboard
                </li>
            </span>
            <span class="flex gap-x-2">
                <img src="/wallet.png" alt="" />
                <li>Carteira</li>
            </span>
            <span class="flex gap-x-2">
                <img src="/transactions.png" alt="" />
                <li>Transações</li>
            </span>
            <span class="flex gap-x-2">
                <img src="/support.png" alt="" />
                <li>Suporte</li>
            </span>
            <span class="flex gap-x-2">
                <img src="/settings.png" alt="" />
                <li>Ajustes</li>
            </span>
            <div class="border border-gray-500/20"></div>
        </ol>
        <span class="flex items-center gap-x-2">
            <h2 class="text-[#F03D3D] bg-[#fcb4b4]/30 rounded-md py-2 px-3 flex gap-x-4">
                <img src="/disconnect.png" alt="" />
                Desconectar
            </h2>
        </span>
    </div>
</template>

<script setup>
import { ref } from "vue";

const isOpen = ref(false);

function handleOpen() {
    isOpen.value = !isOpen.value;
    console.log(isOpen.value);
}
</script>

<style lang="scss" scoped></style>
