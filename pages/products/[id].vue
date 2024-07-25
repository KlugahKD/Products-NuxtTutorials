<template>
    <div>
        <ProductDetails :product="product"/>
    </div>
</template>

<script setup>
import ProductDetails from '../components/ProductDetails.vue';


const { id } = useRoute().params;
const uri = `https://fakestoreapi.com/products/${id}`;

const { data : product } = await useFetch(uri);

if(!product.value){
    throw createError({
        statusCode: 404,
        message: 'Product not found',
        fatal: true
    })
}

definePageMeta({
    layout: 'products',
})

</script>

<style scoped>

</style>