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
    <div class="container-fluid">
        <div class="d-flex flex-column align-items-center">
            <h2 class="mt-5">RECENT CAUSES</h2>
            <hr class="hrs text-warning">
            <span class="mb-4">
                We run projects in over 30 countries in 5 continents
            </span>
        </div>
        <div class="container d-flex mb-3">
            <img class="img-adj" src="../img/HelloIMG1669149317319.jpeg" alt="">
            <img class="img-adj" src="../img/HelloIMG1669149318263.jpeg" alt="">
            <img class="img-adj" src="../img/HelloIMG1669149319450.jpeg" alt="">
            <img class="img-adj" src="../img/HelloIMG1669149321401.jpeg" alt="">
        </div>
    </div>
    <div class="container-fluid p-4 d-flex flex-column align-items-center" style="background-color: #ed6967;">
        <span class="text-light">
            VIEW ALL OUR CAUSES
        </span>
    </div>
</template>

<style>
.img-adj{
    width: 250px;
    gap:5px;
    display: flex;
    justify-content: center;
    flex-direction: row;

}
.container {
    width: 100%;
    flex-wrap: wrap;
    justify-content: space-between;
}
</style>