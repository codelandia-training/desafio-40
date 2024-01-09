<template>
    <div class="bg-white w-56 rounded-xl py-4 pl-4 flex flex-col gap-y-2">
        <h3 class="font-medium text-black/85">{{ title }}</h3>
        <strong>R$ {{ value }}</strong>
        <span
            :class="'text-[#' + textColorPercentage + '] bg-[#' + bgPercentage + ']'"
            class="flex items-center text-[#0BB07B] bg-[#88f5d2]/30 w-fit py-1 px-3 rounded-full"
        >
            <img class="h-2" :src="iconUrl" alt="" />
            <h5>+{{ percentage }}%</h5>
        </span>
    </div>
    <div></div>
</template>

<script setup>
defineProps([
    "title",
    "value",
    "iconUrl",
    "percentage",
    "bgPercentage",
    "textColorPercentage",
]);
</script>

<style lang="scss" scoped></style>
