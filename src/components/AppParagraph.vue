<script>
    export default{
        data() {
            return {
                jumbotron: 'Districandomi tra le cartelle, sono riuscito a creare non solo un titolo ma anche un paragrafo con Vite.'
            }
        }
    };
</script>

<template>
    <div>
        <p> {{ jumbotron }} </p>
    </div>
</template>

<style scoped>
    div {
        padding: 2.5rem 0;
        background-color: #000;
        margin-top: 6.125rem;
        margin-bottom: 4.375rem;
        border-radius: 6.25rem;
        box-shadow: 0 0 .625rem .125rem #7df9ff;
    }

    p {
        text-align: center;
        color: #fff;
        font-size: 1.4em;
        font-weight: 700;
        text-shadow: 0 0 .625rem #fab28b;
    }
</style>