<template>
    <aside
        class="bg-white px-12 h-screen col-span-2 flex flex-col items-center pt-16 gap-y-10"
    >
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
    </aside>
</template>

<script setup></script>

<style lang="scss" scoped></style>
