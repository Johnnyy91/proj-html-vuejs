<template>
  <header class="container-fluid">
    <div id="upper-part" class="row d-flex py-2 justify-content-around">
        <div id="hours" class="d-flex col-6 px-4">
            <span class="px-2"><i class="fa-solid fa-clock"></i></span>
            <p>Open Hours : Mon - Sat 9:00 - 18:00</p>
        </div>
        <div id="contacts" class="d-flex col-6 px-4">
            <span class="px-2"><i class="fa-solid fa-phone"></i></span>
            <p class="pe-4">+ 1 (305) 1234-5678</p>
            <span class="px-2"><i class="fa-solid fa-envelope"></i></span>
            <p class="pe-4"><a href="#">hello@example.com</a></p>
            <span class="px-2"><i class="fa-brands fa-facebook"></i></span>
            <span class="px-2"><i class="fa-brands fa-twitter"></i></span>
            <span class="px-2"><i class="fa-brands fa-linkedin"></i></span>
        </div>
    </div>

    <div id="lower-part" class="row d-flex py-2 justify-content-around">
        <div id="navigation" class="d-flex col-6">
            <div>
                <img src="@/assets/images/image.png" class="logo-img" alt="Nex Gen">
            </div>
            <nav v-for="link in navbartext" :key="link.text" class="d-flex">
                <a href="#" class="search">{{ link.text }}</a>
            </nav>
        </div>
        <div id="principal-title" class="d-flex justify-content-center text-white">
            <div class="col-6 text-center">
                <h1>LEAD CUSTOMER</h1>
                <p>Succesful strategies require data analysis, creativity and customer focus, 
                    taking advantage of the latest tecnologies to offer excelent services</p>
                <button>GET IN TOUCH</button>
                <button>READ MORE</button>
            </div>
        </div>
    </div>
  </header>
</template>

<script>
export default {
name : 'HeaderComponent',
props: {
        navbartext: Array
    }
}
</script>

<style lang="scss" scoped>
#upper-part{
        background-color: #21343e;
        color: white;
    }
#lower-part{
    background-image: url(@/assets/images/hero-image.png);
    background-repeat: no-repeat;
    background-size: cover;
    height: 80vh;
    z-index: -1;
    .logo-img{
        width: 50%;
    }
}    
.search{
    text-decoration: none;
    padding: 0 15px;
}
button{
    border: 1px solid #0d7e7e;
    border-radius: 5%;
    background-color: transparent;
    padding: 10px;
    margin: 0 10px;
}
</style>