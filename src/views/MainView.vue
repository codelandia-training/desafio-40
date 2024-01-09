<template>
    <main class="py-12 px-20">
        <Header />
        <div class="flex gap-x-6">
            <GraficoDeReceitas class="w-1/2" />
            <HistoricoDeTransacoes class="w-1/2" />
        </div>
        <Informacoes />
    </main>
</template>

<script setup>
import Header from "../components/Header.vue";
import GraficoDeReceitas from "../components/GraficoDeReceitas/GraficoDeReceitas.vue";
import HistoricoDeTransacoes from "../components/HistoricoDeTransacoes.vue";
import Informacoes from "../components/Informacoes/Informacoes.vue";
</script>

<style lang="scss" scoped></style>
