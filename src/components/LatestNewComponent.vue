<template>
  <section>
    <div class="container">
        <div class="d-flex justify-content-between py-4">
            <div>
                <h6>OUR EDITORIAL CONTENT</h6>
                <h2>LATEST <h2 class="d-inline-block green">NEWS</h2></h2>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. In quia hic fuga rem dolorum</p>
            </div>
            <div class="align-self-end">
                <button>SEE ALL</button>
            </div>
        </div>
            <div class="d-flex justify-content-between">
                <div class="personal-card first-card text-center d-flex align-items-end">
                    <!--<p><span></span>Marta Kent</p>-->
                    <h5>Increasing  creativity is possible for everyone</h5>
                </div>
                <div class="personal-card second-card text-center d-flex align-items-end">
                    <!--<p><span></span>Marta Kent</p>-->
                    <h5>Increasing creativity is possible for everyone</h5>
                </div>
                <div class="personal-card third-card text-center d-flex align-items-end">
                    <!--<p><span></span>Marta Kent</p>-->
                    <h5>Increasing creativity is possible for everyone</h5>
                </div>
            </div>
    </div>
  </section>
</template>

<script>
export default {
name : 'LatestNewComponent'
}
</script>

<style lang="scss" scoped>
section{
        padding-left: 200px;
        padding-right: 200px;
    }
    .personal-card{
        height: 300px;
        width: 300px;
        border-radius: 5px;
    }
    .first-card{
        background-image: url(@/assets/images/news-1.jpg);
        background-size: cover;

    }
    .second-card{
        background-image: url(@/assets/images/news-2.jpg);
        background-size: cover;
    }
    .third-card{
        background-image: url(@/assets/images/news-3.jpg);
        background-size: cover;
    }
    h5{
        color: white;
        padding-bottom: 10px;
    }
    h6{
        color: #0d7e7e;
        padding: 5px 0;
    }
    p{
        color: hsl(203deg 8% 55%);
        padding: 5px 0;
    }
    button{
        border: 1px solid #0d7e7e;
        border-radius: 5%;
        background-color: #0d7e7e;
        padding: 10px;
        color: white;
    }
    .green {
        background-color: hsl(189deg 40% 90%);
        padding: 10px;
        border-radius: 5px;
        color: hsl(178deg 93% 26%);
    }
</style>