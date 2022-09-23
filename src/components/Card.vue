<template>
    <grid>
        <img v-bind:src="url" :alt="nombre">
        <h2>{{ nombre }}</h2>
        <h3> {{precio}} </h3>
        <h3>Descripcion: </h3>
            <p>{{descripcion}}</p>
    
        
    </grid>
</template>

<script>
import Grid from "./Grid.vue";

    export default {
    props: {
        url: {
            String,
        },
        nombre: {
            String,
        },
        precio: {
            String,
        },
        descripcion: {
            String,
        }
    },
    components: { Grid }
}
</script>

<style scoped>
    div{
        display: inline-block;
        text-align: center;
        border: 1px solid #f2f2f2;
        padding: 1%;
        border-radius: 5px;
        margin: 4px;
    }

    img{
        width: 8rem;
        height: 8rem;
        padding: 0.5rem;
        background: snow;

    }

    a{
        text-decoration: node;
        color: snow;
        background-color: #1F3AFB;
        padding: 0.3rem;
        border-radius: 5px;
        border: 1px solid #f2f2f2;
    }



</style>