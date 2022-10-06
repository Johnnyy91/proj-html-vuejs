<template>
  <footer class="container-fluid">
    <div id="info" class="row">
        <div class="col-3 d-flex flex-column">
            <img src="@/assets/images/image.png" class="logo-img" alt="Nex Gen">
            <p>A Functional HTML template for Corporate & Business</p>
            <span class="px-2"><i class="fa-solid fa-phone pe-3"></i>+ 1 (305) 1234-5678</span>
            <span class="px-2"><i class="fa-solid fa-envelope pe-3"></i><a href="#">hello@example.com</a></span>
            <span class="px-2"><i class="fa-solid fa-location-dot pe-3"></i>Main Avenue, 987</span>
            <button>GET IN TOUCH</button>
        </div>
        <div id="card" class="col-3">
            <h5>About</h5>
            <p><span><i class="fa-solid fa-angle-right"></i></span>The Company</p>
            <p><span><i class="fa-solid fa-angle-right"></i></span>The Company</p>
            <p><span><i class="fa-solid fa-angle-right"></i></span>The Company</p>
            <p><span><i class="fa-solid fa-angle-right"></i></span>The Company</p>
            <p><span><i class="fa-solid fa-angle-right"></i></span>The Company</p>
            <p><span><i class="fa-solid fa-angle-right"></i></span>The Company</p>
        </div>
        <div id="card" class="col-3">
            <h5>Services</h5>
            <p><span><i class="fa-solid fa-angle-right"></i></span>The Company</p>
            <p><span><i class="fa-solid fa-angle-right"></i></span>The Company</p>
            <p><span><i class="fa-solid fa-angle-right"></i></span>The Company</p>
            <p><span><i class="fa-solid fa-angle-right"></i></span>The Company</p>
            <p><span><i class="fa-solid fa-angle-right"></i></span>The Company</p>
            <p><span><i class="fa-solid fa-angle-right"></i></span>The Company</p>
        </div>
        <div id="card" class="col-3">
            <h5>Support</h5>
            <p><span><i class="fa-solid fa-angle-right"></i></span>The Company</p>
            <p><span><i class="fa-solid fa-angle-right"></i></span>The Company</p>
            <p><span><i class="fa-solid fa-angle-right"></i></span>The Company</p>
            <p><span><i class="fa-solid fa-angle-right"></i></span>The Company</p>
            <p><span><i class="fa-solid fa-angle-right"></i></span>The Company</p>
            <p><span><i class="fa-solid fa-angle-right"></i></span>The Company</p>
        </div>
    </div>
  </footer>
</template>

<script>
export default {
name : 'FooterComponent'
}
</script>

<style lang="scss" scoped>
footer{
        background-color: black;
        color: hsl(255deg 6% 74%);
    }
.logo-img{
    max-width: 25%;
}
#card{
    background-color: hsl(240deg 12% 11%);
    width: 300px;
    height: 350px;
    h5{
        color: white;
        padding: 10px;
    }
    span{
        padding: 0 10px;
    }
}
</style>