<template>
<section id="company" class="py-0">
    <div class="container-fluid">
        <div class="row">
            <div class="col-6 py-5">
                <h6>ABOUT THE NETWORK</h6>
                <h2>THE COMPANY</h2>
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Expedita ad ipsum volupt</p>
                <div class="under-box">
                    <div>
                        <h5>ciao</h5>
                        <p>cioa fanculo</p>
                    </div>
                    <div>
                        <h5>ciao</h5>
                        <p>cioa fanculo</p>
                    </div>
                    <div>
                        <h5>ciao</h5>
                        <p>cioa fanculo</p>
                    </div>
                    <div>
                        <h5>ciao</h5>
                        <p>cioa fanculo</p>
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
 }

.under-box {
    width: 100%;
    display: flex;
    flex-wrap: wrap;

    div {
        width: calc(100% / 2)
    }
}
</style>