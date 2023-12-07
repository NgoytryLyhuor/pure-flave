<script setup>

</script>
<template>
    <div class="container-fluid top-bar d-flex justify-content-center align-items-center">
        <span>free shipping on ordered over $75</span>
    </div>
    <div class="container-fluid main-nav">
        <div class="container navbar">
            <div class="row w-100 h-100">
                <div class="col-md-2 d-flex align-items-center justify-content-center logo">
                    <router-link to="/" class="text-decoration-none">
                        <h2 style="font-family: 'Kanit', sans-serif !important;font-weight: 400;">pure flave</h2>
                    </router-link>
                </div>
                <div class="col-md-8 d-flex align-items-center">
                    <router-link class="text-decoration-none link" style="color: #3f583d;" to="/shop">Shop</router-link>
                    <router-link class="text-decoration-none link" style="color: #3f583d;"
                        to="/subscription">Subscription</router-link>
                    <router-link class="text-decoration-none link" style="color: #3f583d;"
                        to="/about_Us">About_Us</router-link>
                    <router-link class="text-decoration-none link" style="color: #3f583d;"
                        to="/contact">Contact</router-link>
                </div>
                <div class="col-md-2 d-flex align-items-center login">
                    <font-awesome-icon style="font-size: 20px;color: #476c43;" class="user" icon="fa-solid fa-user" />
                    <span style="margin-right: 25px;font-size: 18px; margin-left: 5px;color: #476c43;">Log In</span>
                    <font-awesome-icon style="font-size: 21px; color: #476c43;" icon="fa-solid fa-lock" />
                </div>

                <div class="col-10 res-logo">
                    <router-link to="/" class="text-decoration-none">
                        <h2 style="font-family: 'Kanit', sans-serif !important;font-weight: 400;">pure flave</h2>
                    </router-link>
                </div>

                <div class="col-2 res-div-menu p-0 m-0">
                    <div class="box">
                        <div class="bar mb-1"></div>
                        <div class="bar mb-1"></div>
                        <div class="bar mb-1"></div>
                    </div>
                </div>


            </div>
        </div>
    </div>
    <div class="res_menu">

    </div>
</template>
<style scoped>
.top-bar {
    background-color: #d7eac7;
    height: 28px;
    border-bottom: 1px solid #000;
}

.top-bar span {
    color: #476c43;
    font-weight: bold;
    text-transform: uppercase;
    font-size: 14px;
}

.main-nav {
    border-bottom: 1px solid #000;
    background-color: #f9f9f9;
}

.navbar {
    height: 87px;
    width: 80%;
}

.navbar .col-md-2:nth-child(1) h2 {
    color: #476c43;
    font-weight: 700;
}

.navbar .col-md-8 a {
    color: #000;
    font-weight: 400;
    font-size: 17px;
    padding: 10px 20px;
}
.res-logo, .res_menu, .res-div-menu{
    display: none !important;
}


/* S21 Ultra */
@media (max-width: 575.98px) {
    .col-md-8 {
        display: none !important;
    }

    .login {
        display: none !important;
    }

    .user {
        margin-right: 10px;
    }

    .logo {
        display: none !important;
    }


    .res_menu {
        display: none;
        width: 100%;
        position: fixed;
        top: 0;
        left: 0;
        height: 100vh;
        background-color: #476c43;
    }

    .res-logo{
        display: flex !important;
        align-items: center;
        justify-content: start;
    }
    .res-logo h2{
        color: #476c43 !important;
    }
    .bar{
        width: 24px;
        height: 2px;
        background-color: #476c43;
        border-radius: 50px;
    }
    .res-div-menu{
        display: flex !important;
        align-items: center;
        justify-content: end;
    }
    .navbar {
        height: 50px;
        width: 80%;
    }

}</style>