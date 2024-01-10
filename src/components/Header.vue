<template>
    <header class="flex justify-between">
        <div>
            <h1 class="text-2xl">Olá, Antônio</h1>
            <p class="text-black/60">Aqui estão as informações sobre suas vendas.</p>
        </div>
        <div class="md:flex hidden items-center gap-x-8">
            <div class="flex gap-x-4">
                <img
                    @click="handleSearchClick"
                    class="cursor-pointer"
                    src="/search.png"
                    alt=""
                />
                <img src="/bell.png" alt="" />
            </div>
            <div class="flex items-center gap-x-2">
                <img src="/userphoto.png" alt="" />
                <h4>Antônio André</h4>
            </div>
        </div>
    </header>
    <BarraDePesquisa v-if="isOpenSearch" />
</template>

<script setup>
import BarraDePesquisa from "./BarraDePesquisa.vue";
import { ref } from "vue";

const isOpenSearch = ref(false);

function handleSearchClick() {
    isOpenSearch.value = !isOpenSearch.value;
    console.log(isOpenSearch.value);
}
</script>

<style lang="scss" scoped></style>
