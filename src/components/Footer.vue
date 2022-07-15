<template>
<div>
    <div class="main-footer-container">
        <div class="container p-3">
            <div class="row d-flex h-100 align-items-center">
                <div class="col-6 text-white d-flex mt-2">
                    <div class="col-4">
                                <h6>DC COMICS</h6>
                                <ul class="list-unstyled">
                                    <li>ITEM</li>
                                    <li>ITEM</li>
                                    <li>ITEM</li>
                                    <li>ITEM</li>
                                    <li>ITEM</li>
                                    <li>ITEM</li>
                                    <li>ITEM</li>
                                    <li>ITEM</li>
                                </ul>
                                <h6>SHOP</h6>
                                <ul class="list-unstyled">
                                    <li>ITEM</li>
                                    <li>ITEM</li>
                                </ul>
                            </div>
                            <div class="col-4">
                                <h6>DC COMICS</h6>
                                <ul class="list-unstyled">
                                    <li>ITEM</li>
                                    <li>ITEM</li>
                                    <li>ITEM</li>
                                    <li>ITEM</li>
                                    <li>ITEM</li>
                                    <li>ITEM</li>
                                    <li>ITEM</li>
                                    <li>ITEM</li>
                                    <li>ITEM</li>
                                    <li>ITEM</li>
                                    <li>ITEM</li>
                                </ul>
                            </div>
                            <div class="col-4">
                                <h6>DC COMICS</h6>
                                <ul class="list-unstyled">
                                    <li>ITEM</li>
                                    <li>ITEM</li>
                                    <li>ITEM</li>
                                    <li>ITEM</li>
                                </ul>
                            </div></div>
                <div class="col-6 p-5 position-relative"><img class="position-absolute  top-50 start-50 translate-middle" src="../assets/img/dc-logo-bg.png" alt=""></div>
            </div>
        </div>
    </div>
    <div class="container-fluid bg-black">
        <div class="container">
            
              <div class="row d-flex align-items-center  justify-content-between p-5">
            <div class="col-6">
                <button class="btn btn-light">Sign-up NOW</button>
            </div>
            <div class="col-6"><ul class="list-unstyled d-flex justify-content-between">
                                    <li><img src="../assets/img/footer-facebook.png" alt=""></li>
                                    <li><img src="../assets/img/footer-periscope.png" alt=""></li>
                                    <li><img src="../assets/img/footer-pinterest.png" alt=""></li>
                                    <li><img src="../assets/img/footer-youtube.png" alt=""></li>
                                    <li><img src="../assets/img/footer-youtube.png" alt=""></li>
                                </ul></div>
        </div>
        </div>
    </div>
</div>
</template> 

<script>
export default {
    name:'MainFooter'
}
</script>

<style scoped lang="scss">
.main-footer-container{
    background-image: url('../assets/img/footer-bg.jpg');
    background-size: cover;
    height: 40vh;
    background-repeat: no-repeat;
}

li{
    font-weight: 100;
}
</style>