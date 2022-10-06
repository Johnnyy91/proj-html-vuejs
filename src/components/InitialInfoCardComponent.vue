<template>
<section id="initial-info-card">
    <div class="container py-5">
        <div class="row d-flex justify-content-center gap-4">
            <div class="col-3 card py-4 px-4">
                <span class="skin"><i class="fa-solid fa-user-group"></i></span>
                <h5 class="py-3">Human Capital</h5>
                <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Dolore deserunt incidunt culpa ab pariatur
                    iusto ducimus</p>
            </div>
            <div class="col-3 card py-4 px-4">
                <span class="skin"><i class="fa-solid fa-clock-rotate-left"></i></span>
                <h5 class="py-3">Core Business</h5>
                <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Dolore deserunt incidunt culpa ab pariatur
                    iusto
                    ducimus</p>
            </div>
            <div class="col-3 card py-4 px-4">
                <span class="skin"><i class="fa-solid fa-clock"></i></span>
                <h5 class="py-3">Performance</h5>
                <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Dolore deserunt incidunt culpa ab pariatur
                    iusto
                    ducimus</p>
            </div>
        </div>
    </div>
</section>
</template>

<script>
export default {
name : 'InitialInfoCardComponent'
}
</script>

<style lang="scss" scoped>
#initial-info-card {
    background-color: hsl(120deg 21% 95%);
}

.card {
    background-color: white;
    height: 300px;
    border-radius: 5%;
    border: none;

    .skin {
        width: 20%;
        border: 1px solid hsl(189deg 40% 90%);
        border-radius: 20px;
        text-align: center;
        padding: 5px 10px;
        background-color: hsl(189deg 40% 90%);
        color: hsl(180deg 100% 25%);
        font-size: 1.5rem;
    }

    p {
        color: hsl(203deg 8% 55%);
    }
}
</style>