<template>
    <div class="grid grid-cols-12 bg-[#f5f5f5]">
        <Sidebar />
        <section class="col-span-9">
            <MainView />
        </section>
    </div>
</template>

<script setup>
import Sidebar from "./components/Siderbar.vue";
import MainView from "./views/MainView.vue";
</script>

<style lang="scss" scoped></style>
