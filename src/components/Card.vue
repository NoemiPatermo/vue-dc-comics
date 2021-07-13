<template>
  <div class="product-card">
    <div
      class="img-container"
      :style="{ backgroundImage: 'url(' + thumb + ')' }"
    ></div>
    <span>{{ title }}</span>
    <h4>{{ price }}</h4>
  </div>
</template>

<script>
export default {
  name: 'Card',
  props: {
    thumb: String,
    price: String,
    title: String,
    type: String,
  },
};
</script>

<style scoped lang="scss">
.product-card{
  width: calc(100% / 6 );
  padding: 10px;
  .img-container{
    width: 150px;
    height: 160px;
    background-size: cover;
    margin: 20px 0px;
  }
  span{
    font-size: 15px;
    color: white;
  }
  h4{
    margin-top: 10px;
    color: white;
  }
}
</style>