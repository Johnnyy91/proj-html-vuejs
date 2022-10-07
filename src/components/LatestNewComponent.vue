<template>
  <section>
    <div class="container">
        <div class="d-flex justify-content-between">
            <div>
                <p>OUR BUSINESS AREAS</p>
                <h2>EXCELLENCE IN SERVICES</h2>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. In quia hic fuga rem dolorum fugit
                    doloremque</p>
            </div>
            <div class="align-self-end">
                <button>SEE ALL</button>
            </div>
        </div>
            <div class="d-flex justify-content-between">
                <div class="personal-card first-card text-center d-flex align-items-end">
                    <h5>Increasing  creativity is possible for everyone</h5>
                </div>
                <div class="personal-card second-card text-center d-flex align-items-end">
                    <h5>Increasing creativity is possible for everyone</h5>
                </div>
                <div class="personal-card third-card text-center d-flex align-items-end">
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
    }
</style>