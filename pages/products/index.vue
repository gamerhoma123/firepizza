<template>
<div class="py-5">
    <div class="container">
        <div class="row g-3">

            <div class="col-md-3" v-for="(burger , index) in data.data._rawValue" :key="index">
               <ProductCard :product="burger" />
            </div>

        </div>
    </div>

</div>
</template>

<script setup>
const data =await useFetch("https://api.escuelajs.co/api/v1/products");
console.warn(data.data._rawValue);
</script>

<style scoped>
</style>
