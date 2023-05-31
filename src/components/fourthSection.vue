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
    <div class="container-fluid g-0">
        <div class="d-flex flex-column align-items-center">
            <h2 class="mt-5">LATEST ARTICLES</h2>
            <hr class="hrs text-warning">
            <span class="mb-4">
                Together we make all the difference
            </span>
        </div>
        <div class="first g-0"> 
            <div class="first-one border">
                <img class="img-3" src="../img/HelloIMG1669149322752.jpeg" alt="">
                <div class="fs-5 text-warning d-flex m-auto">
                    Understanding community complexities
                </div>
                <p class="fsz-2">
                    Lorem, ipsum dolor sit amet consectetur adipisicing elit. Esse earum mollitia rerum tempore cumque voluptates est neque corporis optio! Voluptas alias minima, dolorem tempora ex necessitatibus unde dicta inventore perferendis!
                </p>
            </div>
            <div class="first-two g-0 d-flex flex-column justify-content-between">
                <div class="container-1 d-flex flex-row">
                    <img class="small-img" src="../img/HelloIMG1669149322752.jpeg" alt="">
                    <div class="container-2 d-flex flex-column">
                        <div class="text-warning mt-0 fsz-3">
                            The human story of uniquiness
                        </div>
                        <div class="fsz-2">
                           Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellendus nobis expedita atque ipsa blanditiis
                        </div>
                    </div>
                </div>
                <div class="container-1 d-flex flex-row">
                    <img class="small-img" src="../img/HelloIMG1669149322752.jpeg" alt="">
                    <div class="container-2 d-flex flex-column">
                        <div class="text-warning mt-0 fsz-3">
                            Sustainable trade tactics
                        </div>
                        <div class="fsz-2">
                           Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellendus nobis expedita atque ipsa blanditiis
                        </div>
                    </div>
                </div>
                <div class="container-1 d-flex flex-row">
                    <img class="small-img" src="../img/HelloIMG1669149322752.jpeg" alt="">
                    <div class="container-2 d-flex flex-column">
                        <div class="text-warning mt-0 fsz-3">
                            Farmers making a difference
                        </div>
                        <div class="fsz-2">
                           Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellendus nobis expedita atque ipsa blanditiis
                        </div>
                    </div>
                </div>
                <div class="container-1 d-flex flex-row">
                    <img class="small-img" src="../img/HelloIMG1669149322752.jpeg" alt="">
                    <div class="container-2 d-flex flex-column">
                        <div class="text-warning mt-0 fsz-3">
                            Meeting remote tribes in Peru
                        </div>
                        <div class="fsz-2">
                           Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellendus nobis expedita atque ipsa blanditiis
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="d-flex justify-content-center mt-3 mb-5">
            <button style="background-color:#ed6967;" type="button" class="text-light btn-pers btn">VIEW ALL OUR ARTICLES</button>
        </div>
        <div>

        </div>
    </div>
</template>

<style>
.container-1 {
    width: 100%;
    height: 23%;
}
.first {
    display: flex;
    justify-content: space-between;
    width: 70%;
    margin: auto;
}
.first-one {
    width: 49%;
    display: flex;
    flex-direction: column;
    gap:10px;
    align-items: end;
}
.first-two {
    width: 49%;
    display: flex;
    flex-direction: column;
}
.img-3{
    width: 100%;
    height: 80%;
}
.fsz-2 {
    font-size: 10px;
}
.fsz-3 {
    font-size: 14px;
}
.small-img {
    width: 40%;
    height: 100%;
}
.btn-pers {
    width: 70%;
    margin: auto;
}
</style>