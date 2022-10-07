<template>
<section id="card-content">
    <div class="container">
        <div class="row">
            <div class="col-12">
                <h6>OUR BUSINESS AREAS</h6>
                <h2>EXCELLENCE IN <h2 class="d-inline-block green">SERVICES</h2> </h2>
                <div class="d-flex justify-content-between">
                    <p class="color-grey">Lorem ipsum dolor sit amet consectetur adipisicing elit. In quia hic fuga rem dolorum fugit
                        doloremque</p>
                    <button>SEE ALL</button>
                </div>
            </div>
            <div class="card-skinning">
                <span><i class="fa-solid fa-cubes"></i></span>
                <h5>Audit and assurance</h5>
                <p>Lorem ipsum dolor sit amet consecutor adipiscing elit</p>
                <button>READ MORE</button>
            </div>
            <div class="card-skinning">
                <span><i class="fa-solid fa-briefcase"></i></span>
                <h5>Financial Advisory</h5>
                <p>Lorem ipsum dolor sit amet consecutor adipiscing elit</p>
                <button>READ MORE</button>
            </div>
            <div class="card-skinning">
                <span><i class="fa-solid fa-chart-simple"></i></span>
                <h5>Analytics and M&A</h5>
                <p>Lorem ipsum dolor sit amet consecutor adipiscing elit</p>
                <button>READ MORE</button>
            </div>
            <div class="card-skinning">
                <span><i class="fa-solid fa-plane"></i></span>
                <h5>Middle Marketing</h5>
                <p>Lorem ipsum dolor sit amet consecutor adipiscing elit</p>
                <button>READ MORE</button>
            </div>
            <div class="card-skinning">
                <span><i class="fa-solid fa-globe"></i></span>
                <h5>Legal Consulting</h5>
                <p>Lorem ipsum dolor sit amet consecutor adipiscing elit</p>
                <button>READ MORE</button>
            </div>
            <div class="card-skinning">
                <span><i class="fa-solid fa-inbox"></i></span>
                <h5>Regulatory risk</h5>
                <p>Lorem ipsum dolor sit amet consecutor adipiscing elit</p>
                <button>READ MORE</button>
            </div>
        </div>
    </div>
</section>
</template>

<script>
export default {
name : 'CardContentComponent'
}
</script>

<style lang="scss" scoped>
#card-content {
    padding-left: 200px;
    padding-right: 200px;
    background-color: black;

    h2 {
        color: white;
    }
    .green{
        background-color: #0d7e7e;
        padding: 10px;
        border-radius: 5px;
    }

    span {
        font-size: 2rem;
        color: hsl(178deg 93% 26%);
    }

    .card-skinning {
        width: calc(100% / 3 - 20px);
        display: flex;
        flex-direction: column;
        flex-wrap: wrap;
        justify-content: space-around;
        height: 350px;
        border: 1px solid black;
        border-radius: 5px;
        background-color: hsl(240deg 12% 11%);
        color: hsl(203deg 8% 55%);
        margin: 10px;
        button{
            width: 40%;
        }
    }

    h5 {
        color: white;
    }

    button {
        border: 1px solid #0d7e7e;
        border-radius: 5%;
        background-color: transparent;
        padding: 10px;
        color: white;
    }
    button:hover{
        background-color: #0d7e7e;
    }
    .color-grey{
        color: hsl(203deg 8% 55%);
        padding: 5px 0;
    }
    h6{
        color: hsl(178deg 93% 26%);
        padding: 5px 0;
    }
}
</style>