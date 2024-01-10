<template>
    <div class="grid md:grid-cols-12 grid-cols-1 bg-[#f5f5f5]">
        <Sidebar class="md:flex hidden" />
        <MobileSidebar class="md:hidden flex" />
        <section class="col-span-10">
            <MainView />
        </section>
    </div>
</template>

<script setup>
import MobileSidebar from "./components/MobileSidebar.vue";
import Sidebar from "./components/Siderbar.vue";
import MainView from "./views/MainView.vue";
</script>

<style lang="scss" scoped></style>
