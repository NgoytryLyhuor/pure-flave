<script setup>
    
</script>
<template>
    <div class="container-fluid top-bar d-flex justify-content-center align-items-center">
        <span>free shipping on ordered over $75</span>
    </div>
    <div class="container-fluid main-nav">
        <div class="container navbar">
            <div class="row w-100 h-100">
                <div class="col-2 d-flex align-items-center justify-content-center">
                    <router-link to="/" class="text-decoration-none"><h2 style="font-family: 'Kanit', sans-serif !important;font-weight: 400;">pure flave</h2></router-link>
                </div>
                <div class="col-8 d-flex align-items-center">
                    <router-link  class="text-decoration-none" style="color: #3f583d;" to="/shop">Shop</router-link>
                    <router-link class="text-decoration-none" style="color: #3f583d;" to="/subscription">Subscription</router-link>
                    <router-link class="text-decoration-none" style="color: #3f583d;" to="/about_Us">About Us</router-link>
                    <router-link class="text-decoration-none" style="color: #3f583d;" to="/contact">Contact</router-link>
                </div>
                <div class="col-2 d-flex align-items-center">
                    <font-awesome-icon style="font-size: 20px;color: #476c43;" icon="fa-solid fa-user"/>
                    <span style="margin-right: 25px;font-size: 18px; margin-left: 5px;color: #476c43;">Log In</span>
                    <font-awesome-icon style="font-size: 21px; color: #476c43;" icon="fa-solid fa-lock" />
                </div>
            </div>
        </div>
    </div>

</template>
<style scoped>
    .top-bar{
        background-color: #d7eac7;
        height: 28px;
        border-bottom: 1px solid #000;
    }
    .top-bar span{
        color: #476c43;
        font-weight: bold;
        text-transform: uppercase;
        font-size: 14px;
    }
    .main-nav{
        border-bottom: 1px solid #000;
        background-color: #f9f9f9;
    }
    .navbar{
        height: 87px;
        width: 80%;
    }
    .navbar .col-2:nth-child(1) h2{
        color: #476c43;
        font-weight: 700;
    }
    .navbar .col-8 a{
        color: #000;
        font-weight: 400;
        font-size: 17px;
        padding: 10px 20px;
    }
</style>