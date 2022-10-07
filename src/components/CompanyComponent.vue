<template>
<section id="company" class="py-0">
    <div class="container-fluid">
        <div class="row">
            <div class="col-6 py-5">
                <h6>ABOUT THE NETWORK</h6>
                <h2><h2 class="text-variation d-inline-block">THE</h2> COMPANY</h2>
                <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Similique quidem sequi quae ullam fuga mollitia vel dolor reprehenderit!</p>
                <div class="under-box">
                    <div>
                        <h5><span><i class="fa-solid fa-globe"></i></span> TRADITION</h5>
                        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit.</p>
                    </div>
                    <div>
                        <h5><span><i class="fa-solid fa-lock"></i></span> SECURITY</h5>
                        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit.</p>
                    </div>
                    <div>
                        <h5><span><i class="fa-solid fa-ribbon"></i></span> CERTIFICATE</h5>
                        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit.</p>
                    </div>
                    <div>
                        <h5><span><i class="fa-solid fa-burst"></i></span> EXPERTISE</h5>
                        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit.</p>
                    </div>
                </div>
            </div>
            <div class="col-6">
                <img src="@/assets/images/about-3.jpg" class="img-fluid" alt="about company">
            </div>
        </div>
    </div>
</section>
</template>

<script>
export default {
name : 'CompanyComponent'
}
</script>

<style lang="scss" scoped>
section{
        padding-left: 200px;
        p{
            color: hsl(203deg 8% 55%);
            padding: 10px 0;
        }
        h6{
            color: hsl(178deg 93% 26%);
            padding: 10px 0;
        }
        span{
            color: hsl(178deg 93% 26%);
        }
 }

 .text-variation{
    color: hsl(178deg 93% 26%);
    background-color: hsl(189deg 40% 90%);
    padding: 10px;
    border-radius: 5px;
 }

.under-box {
    width: 100%;
    display: flex;
    flex-wrap: wrap;
    padding: 20px 0;

    div {
        width: calc(100% / 2)
    }
}
</style>