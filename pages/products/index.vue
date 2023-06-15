<template>
<div class="py-5">
    <div class="container">
        <div class="row g-3">

            <div class="col-md-3" v-for="(burger , index) in 32" :key="index">
                <div class="card" style="width: 18rem;">
                    <div class="image-box">
                        <img src="https://cdn.pixabay.com/photo/2016/03/31/17/53/burger-1293987_640.png" class="card-img-top" alt="...">
                    </div>
                    <div class="card-body">
                        <h5 class="card-title">THE BURGER</h5>
                        <p class="card-text">BURGER</p>
                    </div>
                </div>
            </div>

        </div>
    </div>

</div>
</template>

<script setup>

</script>

<style scoped>
img {
    filter: grayscale()blur(2px) ;
    

}
img:hover{
    filter: none;
    scale: 1.4;
}
.image-box{
    overflow: hidden;
}
</style>
