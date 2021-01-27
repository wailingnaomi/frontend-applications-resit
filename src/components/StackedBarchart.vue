<template>
        <!-- https://stackoverflow.com/questions/48847644/how-to-bind-img-src-to-data-in-vue -->
        <img v-bind:src="require('../../public/'+ stackedChart)">
</template>

<script>
export default {
    name: "StackedBarchart",
    data(){
        return{
            stackedChart: "stacked-barchart.png"
        }
    }
}
</script>