<template>
    <main class="md:py-12 md:px-20 px-4 py-8">
        <Header />
        <div class="md:flex md:flex-row flex-col flex gap-6 mt-8">
            <GraficoDeReceitas class="md:w-1/2 w-full" />
            <HistoricoDeTransacoes class="md:w-1/2 w-full" />
        </div>
        <Informacoes />
        <HistoricoDeCompradores />
    </main>
</template>

<script setup>
import Header from "../components/Header.vue";
import GraficoDeReceitas from "../components/GraficoDeReceitas/GraficoDeReceitas.vue";
import HistoricoDeTransacoes from "../components/HistoricoDeTransacoes.vue";
import Informacoes from "../components/Informacoes/Informacoes.vue";
import HistoricoDeCompradores from "../components/HistoricoDeCompradores/HistoricoDeCompradores.vue";
</script>

<style lang="scss" scoped></style>
