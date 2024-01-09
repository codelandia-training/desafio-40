<template>
    <div class="bg-white p-6 rounded-xl">
        <h1>Gráfico de receitas</h1>
        <Bar :data="data" :options="options" />
    </div>
</template>

<script>
import {
    Chart as ChartJS,
    Title,
    Tooltip,
    Legend,
    BarElement,
    CategoryScale,
    LinearScale,
} from "chart.js";
import { Bar } from "vue-chartjs";
import * as chartConfig from "./chartConfig.js";

ChartJS.register(CategoryScale, LinearScale, BarElement, Title, Tooltip, Legend);

export default {
    name: "App",
    components: {
        Bar,
    },
    data() {
        return chartConfig;
    },
};
</script>
