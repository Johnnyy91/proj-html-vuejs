<template>
  <section>
    <div class="text-center">
      <h5 class="variant">MONTHLY PLANS</h5>
      <h2><h2 class="d-inline-block green">PRICING</h2> TABLE</h2>
      <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Dolore saepe quasi ipsum esse quae molestias Lorem ipsum dolor sit, amet consectetur adipisicing elit.</p>
    </div>
    <div class="card-container">
      <div class="card">
        <span class="hov-effect"><i class="fa-solid fa-arrow-right"></i></span>
        <span class="big"><i class="fa-solid fa-rocket"></i></span>
        <h4>STANDARD</h4>
        <h5>$ 480 / mo</h5>
        <p>Standard accounting<span><i class="fa-solid fa-check"></i></span></p>
        <p>Platform access<span><i class="fa-solid fa-check"></i></span></p>
        <p>Business orientation<span><i class="fa-solid fa-xmark"></i></span></p>
        <p>Dedicated consultant<span><i class="fa-solid fa-xmark"></i></span></p>
        <p>Personal assistance<span><i class="fa-solid fa-xmark"></i></span></p>
      </div>
      <div class="card">
        <p class="position">Most popular</p>
        <span class="hov-effect"><i class="fa-solid fa-arrow-right"></i></span>
        <span class="big"><i class="fa-solid fa-briefcase"></i></span>
        <h4>PROFESSIONAL</h4>
        <h5>$ 890 / mo</h5>
        <p>Standard accounting<span><i class="fa-solid fa-check"></i></span></p>
        <p>Platform access<span><i class="fa-solid fa-check"></i></span></p>
        <p>Business orientation<span><i class="fa-solid fa-xmark"></i></span></p>
        <p>Dedicated consultant<span><i class="fa-solid fa-xmark"></i></span></p>
        <p>Personal assistance<span><i class="fa-solid fa-xmark"></i></span></p>
      </div>
      <div class="card">
        <span class="hov-effect"><i class="fa-solid fa-arrow-right"></i></span>
        <span class="big"><i class="fa-solid fa-gem"></i></span>
        <h4>ULTIMATE</h4>
        <h5>$ 1390 / mo</h5>
        <p>Standard accounting<span><i class="fa-solid fa-check"></i></span></p>
        <p>Platform access<span><i class="fa-solid fa-check"></i></span></p>
        <p>Business orientation<span><i class="fa-solid fa-xmark"></i></span></p>
        <p>Dedicated consultant<span><i class="fa-solid fa-xmark"></i></span></p>
        <p>Personal assistance<span><i class="fa-solid fa-xmark"></i></span></p>
      </div>
    </div>
  </section>
</template>

<script>
export default {
name : 'PriceTableComponent'
}
</script>

<style lang="scss" scoped>
section{
    padding-left: 200px;
    padding-right: 200px;
    background-color: hsl(120deg 21% 95%);
}
h2{
  font-size: 2.5rem;
  padding: 10px 0;
}
.green{
    background-color: hsl(189deg 40% 90%);
    padding: 10px;
    border-radius: 5px;
    color: hsl(178deg 93% 26%);
}
.variant{
  padding: 10px 0;
  color: #0d7e7e;
}
.card-container{
  display: flex;
  justify-content: center;
  padding: 30px 0;
}
.card{
  position: relative;
  margin: 0 15px;
  padding: 30px;
  border-radius: 5px;
  .position{
    position: absolute;
    top: 10px;
    left: 0;
    border: 1px solid #0d7e7e;
    background-color: #0d7e7e;
    color: white;
    border-radius: 5px;
    padding: 5px;
  }
  .big{
    font-size: 2.5rem;
    text-align: center;
    padding: 30px 0;
  }
  span{
    color: #0d7e7e;
    padding: 0 20px;
  }
  h4{
    text-align: center;
    padding: 10px 0;
  }
  h5{
    text-align: center;
    color: #0d7e7e;
    padding: 10px 0;
  }
  p{
    text-align: left;
    padding: 5px 0;
  }
}
.card:hover{
    transform: translate(0, -20px);
   cursor: pointer;
}
.card:hover .hov-effect{
  display: inline;
}
.hov-effect{
  font-size: 1.5rem;
  position: absolute;
  top: 15px;
  right: 0;
  display: none;
}
</style>