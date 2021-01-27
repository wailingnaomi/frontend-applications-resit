<template>
    <h1>Wat voor personenauto zien we het meest in Nederland?</h1>

    <Introduction />

    <section>   
        <chart-title>In de grafiek hieronder kun je zien welke kleuren en automerken populair zijn onder personenauto’s in Nederland.</chart-title>
        <ChangeChart />
        <Info />
    </section>
    
    <conclusion>
        We zien dat een <strong>grijze</strong> gekleurde auto een favoriet is bij personenauto’s en voor de automerken is dat de <strong>volkswagen</strong>. Erg interessant, niet? De vraag is nu; is een grijze volkswagen de auto die je het meest ziet in Nederland?
    </conclusion>
   
   <section>
        <chart-title>Bekijk hier per automerk hoe de kleuren zijn verdeeld</chart-title>
        <StackedBarchart />
        <Info />
   </section>
    
    <conclusion>
        Uit de grafiek kunnen we lezen dat de <strong>grijze</strong> (25) <strong> volkswagen</strong> inderdaad een populaire personenauto is. De vraag die we hebben gesteld; is de grijze volkswagen de personenauto die we het meest zien in Amsterdam? is dus beantwoord met een dikke ja.
    </conclusion>


</template>

<script>
import Introduction from './Introduction';
import ChartTitle from './ChartTitle';
import ChangeChart from './ChangeChart';
import Info from './Info'
import StackedBarchart from './StackedBarchart';
import Conclusion from './Conclusion';

export default {
    name: "Main",
    components: {
        Introduction,
        'chart-title' : ChartTitle,
        ChangeChart,
        Info,
        StackedBarchart,
        'conclusion' : Conclusion
    },
};
</script>

<style scoped>

    section{
        margin: 20em 0;
    }

    h1{
    font-size: 36px;
    margin: 8em 0;
    }

    p{
        margin: 1em 0;
    }

    a{
        color: #000;
        text-decoration: none;
    }

    a:hover{
        color: #CCCCCC;
    }
</style>