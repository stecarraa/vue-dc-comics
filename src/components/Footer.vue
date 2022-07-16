<template>
<div>
    <div class="main-footer-container overflow-hidden ">
        <div class="container p-3">
            <div class="row d-flex h-100 align-items-center">
                <div class="col-6 text-white h-100 d-flex mt-2">
                    <div class="col-4">
                                <h6>DC COMICS</h6>
                                <ul class="list-unstyled text-secondary">
                                    <li>Item</li>
                                    <li>Item</li>
                                    <li>Item</li>
                                    <li>Item</li>
                                    <li>Item</li>
                                    <li>Item</li>
                                    <li>Item</li>
                                    <li>Item</li>
                                </ul>
                                <h6>SHOP</h6>
                                <ul class="list-unstyled text-secondary">
                                    <li>Item</li>
                                    <li>Item</li>
                                </ul>
                            </div>
                            <div class="col-4">
                                <h6>DC COMICS</h6>
                                <ul class="list-unstyled text-secondary">
                                    <li>Item</li>
                                    <li>Item</li>
                                    <li>Item</li>
                                    <li>Item</li>
                                    <li>Item</li>
                                    <li>Item</li>
                                    <li>Item</li>
                                    <li>Item</li>
                                    <li>Item</li>
                                    <li>Item</li>
                                    <li>Item</li>
                                </ul>
                            </div>
                            <div class="col-4">
                                <h6>DC COMICS</h6>
                                <ul class="list-unstyled text-secondary">
                                    <li>Item</li>
                                    <li>Item</li>
                                    <li>Item</li>
                                    <li>Item</li>
                                </ul>
                            </div></div>
                <div class="col-6 p-5 position-relative"><img class="position-absolute  top-50 start-50 translate-middle" src="../assets/img/dc-logo-bg.png" alt=""></div>
            </div>
        </div>
    </div>
    <div class="container-fluid ms-lower-footer-bg">
        <div class="container">
            
              <div class="row d-flex align-items-center  justify-content-between p-5">
            <div class="col-6">
                <button class="btn  btn-outline-primary text-white border-3">Sign-up NOW</button>
            </div>
            <div class="col-6 d-flex align-items-center">
                <div class="text-uppercase ms-main-blue-color fw-bold">follow us</div>
                
                <ul class="list-unstyled d-flex justify-content-between">
                
                                    <li class="m-3"><img src="../assets/img/footer-facebook.png" alt=""></li>
                                    <li class="m-3"><img src="../assets/img/footer-periscope.png" alt=""></li>
                                    <li class="m-3"><img src="../assets/img/footer-pinterest.png" alt=""></li>
                                    <li class="m-3"><img src="../assets/img/footer-youtube.png" alt=""></li>
                                    <li class="m-3"><img src="../assets/img/footer-twitter.png" alt=""></li>
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
    
    background-repeat: no-repeat;
}

li{
    font-weight: 300;
}

.ms-lower-footer-bg{
    background-color: #303030;
}

.ms-main-blue-color{
    color: #0C7CEC;
}
</style>