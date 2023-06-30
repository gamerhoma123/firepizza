<template>
    <div>
        
        <div class="container">
            <div class="row">
                <div class="col-md-4">
                    <img :src="product.images[0]" alt="" class="img-fluid">
                </div>
                <div class="col-md-8">
                    <div>
                        <h1>{{ product.title }}</h1>
                    </div>
                    <div>
                        <p>{{ product.description }}</p>
                    </div>
                    <div>
                        <p>${{ product.price }}</p>
                    </div>
                    <div>
                        <p>{{ product.creationAt }}</p>
                        <p>{{ product.updatedAt }}</p>
                    </div>
                    <div>
                        <p>{{ product.category.name}}</p>
                    </div>
                   <div>
                        <img :src="product.category.image" alt="" class="img-fluid" width="80">
                   </div>
                   <div py-10>
                    <span><i class="fa-solid fa-circle-plus fa-bounce fs-1"></i></span>
                    <span>quantity:1</span>
                    <span><i class="fa-solid fa-circle-minus fa-bounce fs-1"></i></span>
                   </div>
                   
                    
                </div>
            </div>
        </div>

    </div>
</template>

<script setup>
const route = useRoute();
const { data: product } = await useFetch(`https://api.escuelajs.co/api/v1/products/${route.params.id}`);
</script>

<style scoped>

</style>