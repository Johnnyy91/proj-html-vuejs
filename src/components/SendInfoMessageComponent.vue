<template>
<section id="send-info-message">
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-6">
                <p>SEND A MESSAGE</p>
                <h2>GET IN TOUCH</h2>
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
                <p class="pe-4"><span class="px-2"><i class="fa-solid fa-phone"></i></span> + 1 (305) 1234-5678</p>
                <p class="pe-4"><a href="#"><span class="px-2"><i class="fa-solid fa-envelope"></i></span>
                        hello@example.com</a></p>
                <p class="pe-4"><span class="px-2"><i class="fa-solid fa-phone"></i></span> + 1 (305) 1234-5678</p>
                <button>VIEW MAP</button>
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
</style>