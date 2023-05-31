<script>
import { store } from '../store';
export default {
    data(){
        return {
            store,
        
        };
    }
}
</script>

<template>
    <div class="container-one d-flex img flex-column align-items-center">
        <h1 class="text-light mt-5">Change a life today</h1>
        <p class="paragraf text-light fsz-3 text-center ">As long as poverty, injustice & inequity persist, none of us can truly rest. It doesn't take much to change a life, Get in touch today and start making the difference</p>
        <div class=" buttons-space d-flex">
            <button type="button" class="rounded-0 btn btn-outline-light">VOLUNTEER</button>
            <button type="button" class="rounded-0 btn btn-outline-light">DONATE NOW</button>
        </div>
    </div>
    <div class="d-flex flex-column align-items-center mt-4 mb-4">
        <img class="dimens" src="../img/HelloIMG1669149314987.png" alt="">
    </div>
    <div style="background-color:#e5e5e5" class="pt-4 pb-4 d-flex justify-content-center">
        @ Copyright 2012 - 2022 | Avada Theme by-<span><a style="text-decoration: none;" class="text-warning" href="#">themeFusion</a></span> | All Rights Reserved | Powered by-<span><a style="text-decoration: none;" class="text-warning" href="#">themeFusion</a> </span>

    </div>
</template>

<style>
.paragraf {
    width: 60%;
}
.buttons-space {
    width: 40%;
    justify-content: center;
    gap: 15px;
}
.dimens {
    width: 25%;
}
</style>