<template>
  <div >

    <div class="ms-container">
    <div class="row mt-2 mb-2">
        <div class="col-12 d-flex justify-content-between align-items-center">
           
                <img class="" src="../assets/img/dc-logo.png" alt="">
                 
                <ul class="text-uppercase">
                    <li class="pb-5">Characters</li>
                    <li class="pb-5">Comics</li>
                    <li class="pb-5">Moivies</li>
                    <li class="pb-5">Tv</li>
                    <li class="pb-5">Games</li>
                    <li class="pb-5">Collectibles</li>
                    <li class="pb-5">Videos</li>
                    <li class="pb-5">Fans</li>
                    <li class="pb-5">News</li>
                    <li class="pb-5">Shop</li>
                </ul>
            
        </div>
    </div>
    </div>
    <div class="jumbotron">
  <img src="../assets/img/jumbotron.jpg" alt="">
</div>
  
  </div>
</template>

<script>
export default {
  name: 'MainHeader',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

.ms-container{
  width: 80%;
  margin: 0 auto;
}
li{
    list-style: none;
    display: inline;
    padding: 1rem;
    &:hover{
      color: #0282F9;
      border-bottom: 0.5rem solid  #0282F9;
    }
}

.jumbotron{
  height: 40vh;
  width: 100%;
  img {
          width: 100%;
          object-fit: cover;
         
        }
}


</style>
