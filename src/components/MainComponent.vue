<template>
  <main>
    <section id="initial-info-card">
        <div class="container-fluid py-5">
            <div class="row d-flex justify-content-center gap-4">
                <div class="col-4 card py-4 px-4">
                    <span class="skin"><i class="fa-solid fa-user-group"></i></span>
                    <h5 class="py-3">Human Capital</h5>
                    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Dolore deserunt incidunt culpa ab pariatur iusto ducimus</p>
                </div>
                <div class="col-4 card py-4 px-4">
                    <span class="skin"><i class="fa-solid fa-clock-rotate-left"></i></span>
                    <h5 class="py-3">Core Business</h5>
                    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Dolore deserunt incidunt culpa ab pariatur iusto
                        ducimus</p>
                </div>
                <div class="col-4 card py-4 px-4">
                    <span class="skin"><i class="fa-solid fa-clock"></i></span>
                    <h5 class="py-3">Performance</h5>
                    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Dolore deserunt incidunt culpa ab pariatur iusto
                        ducimus</p>
                </div>
            </div>
        </div>
    </section>

    <section id="company">
        <div class="container-fluid">
            <div class="row">
                <div class="col-6 py-5">
                    <h6>ABOUT THE NETWORK</h6>
                    <h2>THE COMPANY</h2>
                    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Expedita ad ipsum volupt</p>
                </div>
                <div class="col-6">
                    <img src="@/assets/images/about-3.jpg" class="img-fluid" alt="about company">
                </div>
            </div>
        </div>
    </section>

    <section id="card-content">
        <div class="container-fluid">
            <div class="row">
                <div class="col-12">
                    <p>OUR BUSINESS AREAS</p>
                    <h2>EXCELLENCE IN SERVICES</h2>
                    <div class="d-flex">
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. In quia hic fuga rem dolorum fugit doloremque</p>
                        <button>SEE ALL</button>
                    </div>
                </div>
                <div class="col-4 card-skinning">
                    <span><i class="fa-solid fa-cubes"></i></span>
                    <h5>Audit and assurance</h5>
                    <p>Lorem ipsum dolor sit amet consecutor adipiscing elit</p>
                    <button>READ MORE</button>
                </div>
                <div class="col-4 card-skinning">
                    <span><i class="fa-solid fa-briefcase"></i></span>
                    <h5>Financial Advisory</h5>
                    <p>Lorem ipsum dolor sit amet consecutor adipiscing elit</p>
                    <button>READ MORE</button>
                </div>
                <div class="col-4 card-skinning">
                    <span><i class="fa-solid fa-chart-simple"></i></span>
                    <h5>Analytics and M&A</h5>
                    <p>Lorem ipsum dolor sit amet consecutor adipiscing elit</p>
                    <button>READ MORE</button>
                </div>
                <div class="col-4 card-skinning">
                    <span><i class="fa-solid fa-plane"></i></span>
                    <h5>Middle Marketing</h5>
                    <p>Lorem ipsum dolor sit amet consecutor adipiscing elit</p>
                    <button>READ MORE</button>
                </div>
                <div class="col-4 card-skinning">
                    <span><i class="fa-solid fa-globe"></i></span>
                    <h5>Legal Consulting</h5>
                    <p>Lorem ipsum dolor sit amet consecutor adipiscing elit</p>
                    <button>READ MORE</button>
                </div>
                <div class="col-4 card-skinning">
                    <span><i class="fa-solid fa-inbox"></i></span>
                    <h5>Regulatory risk</h5>
                    <p>Lorem ipsum dolor sit amet consecutor adipiscing elit</p>
                    <button>READ MORE</button>
                </div>
            </div>
        </div>
    </section>
  </main>
</template>

<script>
export default {
name : 'MainComponent'
}
</script>

<style lang="scss" scoped>
#initial-info-card{
    background-color: hsl(120deg 21% 95%);
}
.card{
    background-color: white;
    width: 300px;
    height: 300px;
    border-radius: 5%;
    border: none;
    .skin{
        width: 20%;
        border: 1px solid hsl(189deg 40% 90%);
        border-radius: 20px;
        text-align: center;
        padding: 5px 10px;
        background-color: hsl(189deg 40% 90%);
        color: hsl(180deg 100% 25%);
        font-size: 1.5rem;
    }
    p{
        color: hsl(203deg 8% 55%);
    }
}
#card-content{
    background-color: black;
    h2{
        color: white;
    }
    span{
        font-size: 2rem;
        color: hsl(178deg 93% 26%);
    }
    .card-skinning{
        border: 1px solid black;
        background-color: hsl(240deg 12% 11%);
        color: hsl(203deg 8% 55%);
    }
    h5{
        color: white;
    }
    button{
        border: 1px solid #0d7e7e;
        border-radius: 5%;
        background-color: transparent;
        padding: 10px;
        color: white;
    }
}
</style>