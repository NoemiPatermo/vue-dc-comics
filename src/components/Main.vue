<template>
    <div class="main-box ">
        <div class="row">
        <Card
          v-for="(element, index) in comics"
          :key="index"
          :thumb="element.thumb"
          :price="element.price"
          :title="element.series"
          :type="element.type"
        />
      </div> 
    </div>
</template>

<script>
import Card from './Card.vue';// qui importi il tuo component Card

export default {
    name: 'Main',
    components: { // elenchi i  tuoi components
        Card,
    },
    props: { //indica che è un array, usi la coppia chiave-valore
        comics: Array,
    },
    created () {
        console.log(this.comics);
    }
};
</script>



<style lang="scss" scoped>
    .main-box{
        background-color: black;
        .row{
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 30px;
        }
    }
</style>