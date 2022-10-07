<template>
  <header>
    <div id="upper-part">

        <div id="hours">
            <span><i class="fa-solid fa-clock"></i></span>
            <p>Open Hours : Mon - Sat 9:00 - 18:00</p>
        </div>

        <div id="contacts">
            <span><i class="fa-solid fa-phone"></i></span>
            <p>+ 1 (305) 1234-5678</p>
            <span><i class="fa-solid fa-envelope"></i></span>
            <p><a href="#">hello@example.com</a></p>
            <span><i class="fa-brands fa-facebook"></i></span>
            <span><i class="fa-brands fa-twitter"></i></span>
            <span><i class="fa-brands fa-linkedin"></i></span>
        </div>
    </div>

    <div id="lower-part">

        <div id="navigation">
            <div>
                <img src="@/assets/images/image.png" class="logo-img" alt="Nex Gen">
            </div>
            <div class="navlink">
                <nav v-for="link in navbartext" :key="link.text">
                    <a href="#" class="search">{{ link.text }}</a>
                </nav>
            </div>
        </div>
        <div id="principal-title">
                <h1>LEAD ~ CUSTOMER</h1>
                <p>Succesful strategies require data analysis, creativity and customer focus, 
                    taking advantage of the latest tecnologies to offer excelent services</p>
                    <div>
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
    color: hsl(240deg 3% 93%);
    display: flex;
    justify-content: space-around;
}
#hours{
    display: flex;
    padding: 15px;
    span{
        padding: 0 15px;
    }
}
#contacts{
    display: flex;
    padding: 15px;
    span{
        padding: 0 15px;
    }
    a{
        color: hsl(240deg 3% 93%);
        text-decoration: none;
    }
}

#lower-part{
    background-image: url(@/assets/images/hero-image.png);
    background-repeat: no-repeat;
    background-size: cover;
    height: 80vh;
    .logo-img{
        width: 30%;
        margin-left: 10px;
    }
}    
#navigation{
    display: flex;
    justify-content: space-around;
    padding: 15px;
}

.navlink{
    display: flex;
    a{
        color: hsl(240deg 3% 93%);
        margin-left: 10px;
        padding: 10px;
    }
    a:hover{
        background-color: #0d7e7e;
        border-radius: 5px;
    }
}

.search{
    text-decoration: none;
}

#principal-title{
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 100%;
    text-align: center;
    padding-top: 150px;
    h1{
        color: white;
        font-size: 3rem;
        font-weight: 600;
        padding: 15px 0;
    }
    p{
        color: hsl(240deg 3% 93%);
        padding: 10px 0;
        width: 600px;
    }
}

button{
    border: 1px solid #0d7e7e;
    border-radius: 5%;
    background-color: transparent;
    padding: 10px 20px;
    margin: 0 10px;
    color: white;
}

button:hover {
    background-color: #0d7e7e;
    border-radius: 5px;
}
</style>