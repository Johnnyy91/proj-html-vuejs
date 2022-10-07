<template>
  <div class="container-fluid py-5">
    <div class="row d-flex justify-content-center">
        <div class="col-4 text-white py-5">
            <p class="green-">NEWSLETTER</p>
            <h2><h2 class="d-inline-block green">KNOW</h2> FIRST</h2>
            <p class="grey">Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolore facere maiores asperiores fugit nihil</p>
        </div>
        <div class="col-4 d-flex flex-column py-5">
            <input type="text" placeholder="Name">
            <input type="email" placeholder="Email">
            <button>SUBSCRIBE</button>
        </div>
    </div>
  </div>
</template>

<script>
export default {
name : 'NewsletterComponent'
}
</script>

<style lang="scss" scoped>
.container-fluid{
        background-image: url(@/assets/images/bg-1.jpg);
        background-size: cover;
        background-repeat: no-repeat;
        .green-{
            color: #0d7e7e;
        }
        .grey{
            color: hsl(203deg 8% 55%);
        }
    }

    input{
        width: 70%;
        height: 40px;
        margin: 5px;
        background-color: hsl(240deg 3% 93%);
        border: none;
        border-radius: 5px;
    }

    button {
         border: none;
         border-radius: 5%;
         background-color: #0d7e7e;
         padding: 10px;
         color: white;
         width: 30%;
         margin: 5px;
    }
    button:hover{
        background-color: transparent;
    }
    .green {
        background-color: #0d7e7e;
        padding: 10px;
       border-radius: 5px;
   }
</style>