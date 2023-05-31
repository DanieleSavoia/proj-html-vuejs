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
    <div class="container-fluid d-flex g-0">
        <div class="container-left d-flex flex-column align-items-start ps-3">
            <h2 class="pt-3">
                EVERY MOMENT COUNTS
            </h2>
            <hr class="hrs text-warning">
            <p class="mt-4">
                Lorem ipsum dolor sit, amet consectetur adipisicing elit. Fugit sint aliquid consectetur, ut quia obcaecati. Eum, alias, architecto minus sapiente nesciunt, minima repellendus ad deleniti vero asperiores voluptatum autem laudantium!
            </p>
            <p class="mt-4">
                Lorem ipsum dolor sit, amet consectetur adipisicing elit. Fugit sint aliquid consectetur, ut quia obcaecati. Eum, alias, architecto minus sapiente nesciunt, minima repellendus ad deleniti vero asperiores voluptatum autem laudantium!
            </p>
            <p class="mt-4">
                Lorem ipsum dolor sit, amet consectetur adipisicing elit. Fugit sint aliquid consectetur, ut quia obcaecati. Eum, alias, architecto minus sapiente nesciunt, minima repellendus ad deleniti vero asperiores voluptatum autem laudantium!
            </p>
            <button type="button" class="btn btn-warning text-light mb-3">OUR MISSION</button>
        </div>
        <div class="container-right text-light img-2 d-flex flex-column align-items-center justify-content-around">
            <div>
                <div class="d-flex flex-row align-items-center justify-content-center">
                    <i class="fa-regular fa-heart"></i>
                    <span>2033</span>
                </div>
                <div>
                    Volunters worldwide
                </div>
            </div>
            <div>
                <div class="d-flex flex-row align-items-center justify-content-center">
                    <i class="fa-solid fa-earth-americas"></i>
                    <span>132</span>
                </div>
                <div>
                    Active projects
                </div>
            </div>
            <div>
                <div class="d-flex flex-row align-items-center justify-content-center">
                    <i class="fa-solid fa-dollar-sign"></i>
                    <span>3.8M</span>
                </div>
                <div>
                    Donated
                </div>
            </div>
            
            <!--<div>
                <i class="fa-solid fa-earth-americas"></i>
                <span>132</span>
            </div>
            <div>
                Active projects
            </div>
            <div>
                <i class="fa-solid fa-dollar-sign"></i>
                <span>3.8M</span>
            </div>
            <div>
                Donated
            </div>-->
        </div>
    </div>
</template>

<style>
.container-left {
    width:80%;
   

}
.container-right {
    width: 20%;
}
.hrs {
    width: 30%;
    border-top: 3px solid #fec96b;
}
.img-2 {
    background-position: center;
    background-size: 745px;
    background-repeat: no-repeat;
    background-image: url("../img/nero-mappa-del-mondo-delinea-isolato-su-bianco-ehdfxa.jpg");
}
</style>