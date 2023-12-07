<template>
    <div class="container-fluid" style="background-color: #f9f9f9;border-bottom: 1px solid #000;">
        <div class="container" style="width: 80%;padding-top: 50px; padding-bottom: 50px;">
            <h1>Get in Touch</h1>
            <div class="container-fluid p-0 m-0">

                <div class="d-flex justify-content-between mt-5">
                    <div class="item">
                        <p>Fill in the form with your questions, comments and concerns, and we will get right back to you. </p>
                        <div class="container-fluid hr"></div>
                        <h4>Other ways to reach us</h4>
                        <div class="container-fluid p-0 m-0 d-flex justify-content-between">
                            <div class="sub-item">
                                <p class="p-0 m-0">Wholesale enquiries:</p>
                                <a href="info@mysite.com">info@mysite.com</a>
                                <p>Address: <br>500 Terry Francine St.<br>San Francisco,<br>CA 94158</p>
                            </div>
                            <div class="sub-item">
                                <p class="p-0 m-0">PR, press or partnerships:</p>
                                <a href="info@mysite.com">info@mysite.com</a>
                            </div>
                        </div>
                    </div>
                    <div class="item">
                        <form action="" class="w-100 p-0 m-0">
                            <div class="container-fluid p-0 m-0 d-flex justify-content-between mb-5">
                                <div class="sub-item-right">
                                    <p>First Name *</p>
                                    <input type="text">
                                </div>
                                <div class="sub-item-right">
                                    <p>Last Name *</p>
                                    <input type="text">

                                </div>
                            </div>
                            <div class="form-group mb-5">
                                <p>Email *</p>
                                <input type="text">
                            </div>
                            <div class="form-group">
                                <p>Message</p>
                                <textarea name="" id="" cols="30" rows="3"></textarea>
                            </div>
                            <div class="form-group mt-5">
                                <button>Submit</button>
                            </div>
                        </form>
                    </div>
                </div>


            </div>
        </div>
    </div>
</template>

<style scoped>
h1 {
    font-size: 50px;
    font-weight: 700;
    color: #3d5a23;
    font-family: 'Kanit', sans-serif !important;
}

.item {
    width: 480px;
    position: relative;
}

.hr {
    background-color: #000 !important;
    height: 0.6px;
    margin: 45px 0;
}

h4 {
    color: #3d5a23;
    font-family: 'Kanit', sans-serif !important;
}

.sub-item {
    width: 48%;
}
p{
    font-size: 18px;
    color: #3d5945;
}
.sub-item p {
    font-size: 18px;
    margin-top: 40px !important;
}

.sub-item a {
    color: #3d5a23;
    font-size: 18px;
}
.sub-item-right{
    width: 47%;
}
input{
    width: 100%;
    border: none;
    background-color: #f9f9f9;
    border-bottom: 1px solid #000;
}
input:focus{
    outline: none;
    border-bottom: 3px solid #fa9878;
}
textarea{
    width: 100%;
    border: none;
    border-bottom: 1px solid #000;
    background-color: #f9f9f9;
}
textarea:focus{
    outline: none;
}
input:hover, textarea:hover{
    border-bottom: 2px solid #000;
}
button{
    padding: 12px 50px;
    border-radius: 50px;
    border: 1px solid #3d5945;
    background-color: #e2e2f2;
    float: right;
    color: #3d5945;
}
</style>