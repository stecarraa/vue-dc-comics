<template>
  <div class="card">

    <div class="comic-img-container ">
        <img :src="thumbnail" :alt="series">
    </div>
    <h6 class="">{{ series }}</h6>

  </div>
</template>

<script>
export default {
    props: {
        thumbnail: String,
        price: String,
        series: String,
        type: String,
    }
}
</script>

<style lang="scss" scoped>
.card{
width: calc((100% / 6 ) - 20px);
}

.comic-img-container{
    width: 250px;
    height: 250px;

}
img{
height: 100%;
object-fit: contain;
 }
</style>