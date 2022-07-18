<template>
  <div class="card">

    <div class="comic-img-container">
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

</style>