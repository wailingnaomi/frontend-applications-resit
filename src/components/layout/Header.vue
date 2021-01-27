<template>
    <header>
        <h1>De auto in de stad</h1>
        <div></div>
    </header>
</template>

<script>
export default {
    name: "Header"
}
</script>

<style scoped>
    header h1{
        color: #333;
        text-align: center;
        padding: 10px 10px 0 10px;
        
    }

    header h1:after{
        content: "";
        display: block;
        background-color: #ccc;
        width: 10em;
        height: .5em;
        margin-left: auto;
        margin-right: auto;
        margin-top: -.6em;
    }

</style>