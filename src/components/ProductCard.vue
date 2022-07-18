<template>
  <div class="card">

    <div class="comic-img-container ">
        <img :src="thumbnail" :alt="series">
    </div>
    <h4>{{ series }}</h4>

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

<style>
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
object-position: top;
    }
</style>