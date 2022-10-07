<template>
  <footer class="container-fluid">
    <div class="container">
        <div id="info" class="row">
            <div class="col-3 d-flex flex-column justify-content-between">
                <img src="@/assets/images/image.png" class="logo-img" alt="Nex Gen">
                <p>A Functional HTML template for Corporate & Business</p>
                <span class="px-2 "><i class="fa-solid fa-phone pe-3"></i>+ 1 (305) 1234-5678</span>
                <span class="px-2"><i class="fa-solid fa-envelope pe-3"></i><a href="#">hello@example.com</a></span>
                <span class="px-2"><i class="fa-solid fa-location-dot pe-3"></i>Main Avenue, 987</span>
                <button>GET IN TOUCH</button>
            </div>
            <div id="card">
                <h5>About</h5>
                <p v-for="(link, index) in footerlink" :key="index"><span><i class="fa-solid fa-angle-right"></i></span>{{link.about}}</p>
            </div>
            <div id="card">
                <h5>Services</h5>
                <p v-for="(link, index) in footerlink" :key="index"><span><i class="fa-solid fa-angle-right"></i></span>{{link.service}}</p>
            </div>
            <div id="card">
                <h5>Support</h5>
                <p v-for="(link, index) in footerlink" :key="index"><span><i class="fa-solid fa-angle-right"></i></span>{{link.inst}}</p>
            </div>
        </div>
    </div>
  </footer>
</template>

<script>
export default {
name : 'FooterComponent',
props : {
    footerlink : Array
}

}
</script>

<style lang="scss" scoped>
footer{
    background-color: black;
    color: hsl(255deg 6% 74%);
    padding-left: 200px;
    padding-right: 200px;
}

#info{
    padding: 100px 0;
    button {
        width: 70%;
        border: 1px solid #0d7e7e;
        border-radius: 5%;
        background-color: transparent;
        color: white;
        margin: 10px 0;
    }
}

.logo-img{
    max-width: 40%;
    margin: 10px 0;
}
#card{
    background-color: hsl(240deg 12% 11%);
    width: 200px;
    height: 300px;
    margin-left: 15px;
    border-radius: 5px;
    h5{
        color: white;
        padding: 10px;
    }
    span{
        padding: 0 10px;
    }
}
</style>