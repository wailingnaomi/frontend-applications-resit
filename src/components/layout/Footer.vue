<template>
    <footer>
        <p>De data die voor de grafieken zijn gebruikt, komt van <a href="https://opendata.rdw.nl/Voertuigen/Open-Data-RDW-Gekentekende_voertuigen/m9d7-ebf2" target="_blank">Open Data RDW: Gekentekende voertuigen</a>. De waardes voor de grafieken zijn gefilterd op 26 januari 16:15. De gefilterde data kunt u hier vinden: <a href="https://github.com/wailingnaomi/frontend-applications-resit" target="_blank">Github - Naomi Cheung</a></p>
    </footer>
</template>

<script>
export default {
    name: "Footer"
}
</script>

<style scoped>
    footer{
        font-size: 12px;
        background-color: #CCCCCC;
        padding: 1em;
    }

    footer p, a{
        color: #333;
    }

    a:hover{
        color: #f4f4f4;
    }

</style>