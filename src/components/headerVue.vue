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
    <div class="container-fluid img">
        <div class="d-flex justify-content-between">
            <div class="logo">
            <img src="../img/HelloIMG1669149314369.png" alt="">
        </div>
        <ul class="nav nav-pills mt-2">
            <li class="nav-item">
                <a class="nav-link text-light" href="#">Home</a>
            </li>
            <li class="nav-item">
                <a class="nav-link text-light" href="#">Mission</a>
            </li>
            <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle text-light" data-bs-toggle="dropdown" href="#" role="button" aria-expanded="false">Causes</a>
            <ul class="dropdown-menu">
                <li><a class="dropdown-item" href="#">1</a></li>
                <li><a class="dropdown-item" href="#">2</a></li>
                <li><a class="dropdown-item" href="#">3</a></li>
            </ul>
            </li>
            <li class="nav-item">
                <a class="nav-link text-light" href="#">Journal</a>
            </li>
            <li class="nav-item">
                <a class="nav-link active bg-warning text-light rounded-0" aria-current="page" href="#">Donate</a>
            </li>
        </ul>
        </div>
        <div class="d-flex  justify-content-end">
            <a href="#"><i class="text-dark fa-solid fa-gift bg-light  p-2 rounded"></i></a>
        </div>
        <div class="d-flex  justify-content-end">
            <a href="#"><i class="text-light fa-solid fa-gift bg-primary mt-3 p-2 rounded"></i></a>
        </div>
        <div class="container-one d-flex  flex-column align-items-center">
            <h1 class="text-light">make the difference</h1>
            <p class="text-light">As long as poverty, injustice & inequity persist, none of us can truly rest</p>
            <div class="d-flex">
                <button type="button" class="btn btn-outline-light">Our Mission</button>
                <button type="button" class="btn btn-outline-warning">Donate now</button>
            </div>
        </div>
    </div>
</template>

<style>
.img {
    background-image: url(../img/HelloIMG1669149393797.jpeg);
    background-size: cover;
    
}
.container-one {
    height: 300px;
}
</style>