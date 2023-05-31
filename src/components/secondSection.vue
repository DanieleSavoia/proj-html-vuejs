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
    <div class="container-fluid img-1">
        <div class="d-flex flex-column align-items-center">
            <h2 class="mt-5 text-light">OUR VALUES</h2>
            <hr class="hrs text-warning">
            <span class="text-light mb-4">Think Big. Act Bigger</span>
        </div>
        <div class="container-one d-flex flex-row align-items-center justify-content-between">
            <div class="d-flex flex-column align-items-center text-light">
                <i class="fa-sharp fa-solid fa-droplet text-warning fs-1"></i>
                <span class="mt-3">Clear Water</span>
                <p class="fsz mt-4">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorem, impedit consequuntur aliquid.
                </p>
                <button type="button" class="btn btn-warning text-light mb-3">LEARN MORE</button>
            </div>
            <div class="d-flex flex-column align-items-center text-light">
                <i class="fa-solid fa-stethoscope text-warning fs-1"></i>
                <span class="mt-3">Vaccination</span>
                <p class="fsz mt-4">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorem, impedit consequuntur aliquid.
                </p>
                <button type="button" class="btn btn-warning text-light mb-3">LEARN MORE</button>
            </div>
            <div class="d-flex flex-column align-items-center text-light">
                <i class="fa-solid fa-graduation-cap text-warning fs-1"></i>
                <span class="mt-3">Education</span>
                <p class="fsz mt-4">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorem, impedit consequuntur aliquid.
                </p>
                <button type="button" class="btn btn-warning text-light mb-3">LEARN MORE</button>
            </div>
            <div class="d-flex flex-column align-items-center text-light">
                <i class="fa-brands fa-pagelines text-warning fs-1"></i>
                <span class="mt-3">Clear Water</span>
                <p class="fsz mt-4">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorem, impedit consequuntur aliquid.
                </p>
                <button type="button" class="btn btn-warning text-light mb-3">LEARN MORE</button>
            </div>
        </div>
    </div>
</template>
<style>
.hrs {
    width: 30%;
    border-top: 4px solid #fec96b;
}
.fsz {
    font-size: 16px;
    text-align: center;
    width: 50%;
}
</style>