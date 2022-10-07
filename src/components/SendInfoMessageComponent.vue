<template>
<section id="send-info-message">
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-6">
                <h6 class="green">SEND A MESSAGE</h6>
                <h2>GET IN <h2 class="d-inline-block variant-color">TOUCH</h2></h2>
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Dignissimos, fugiat</p>
                <div class="send-date">
                    <input type="text" placeholder="Name">
                    <input type="email" placeholder="Email">
                    <input type="text" placeholder="Phone">
                    <select class="text-black-50">
                        <option>More Info</option>
                    </select>
                    <textarea cols="30" rows="5" placeholder="Message"></textarea>
                    <button>SEND</button>
                </div>
            </div>
            <div class="col-3">
                <h5>Example Inc.</h5>
                <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit</p>
                <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit</p>
                <p class="pe-4 color-green"><span class="px-2 skin"><i class="fa-solid fa-phone"></i></span> + 1 (305) 1234-5678</p>
                <p class="pe-4 color-green"><a href="#"><span class="px-2 skin"><i class="fa-solid fa-envelope"></i></span>hello@example.com</a></p>
                <p class="pe-4 color-green"><span class="px-2 skin"><i class="fa-solid fa-location-dot"></i></span>Main Avenue, 987</p>
                <button class="normal">VIEW MAP</button>
            </div>
        </div>
    </div>
</section>
</template>

<script>
export default {
name : 'SendInfoMessageComponent'
}
</script>

<style lang="scss" scoped>
.send-date {
    &>* {
        width: calc(100% / 2 - 10px);
        margin: 5px;
        background-color: hsl(240deg 3% 93%);
        border: none;
    }

    textarea {
        width: 100%;
    }

    button {
        border: none;
        border-radius: 5%;
        background-color: #0d7e7e;
        padding: 10px;
        color: white;
        width: 15%;
    }
}
.variant-color{
    color: hsl(178deg 93% 26%);
    background-color: hsl(189deg 40% 90%);
    padding: 10px;
    border-radius: 5px;
}
h6{
    padding: 5px 0;
}
h2{
    padding: 5px 0;
}
a{
    color: #0d7e7e;
}
.skin {
    width: 50px;
    border: 1px solid hsl(189deg 40% 90%);
    border-radius: 50%;
    text-align: center;
    padding: 5px 10px;
    background-color: hsl(189deg 40% 90%);
    color: hsl(180deg 100% 25%);
}
.color-green{
    color: #0d7e7e;
}
.green{
    color: #0d7e7e;
}
.normal{
    border: 1px solid #0d7e7e;
    background-color: transparent;
    color: #0d7e7e;
    border-radius: 5px;
    padding: 5px 10px;
}
.normal:hover{
    background-color: #0d7e7e;
    color: white;
}
</style>