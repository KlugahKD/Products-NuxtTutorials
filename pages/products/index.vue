<template>
    <div>
        <div class="grid grid-cols-4 gap-5">
            <div v-for="p in products" :key="p.id">
                <ProductCard :product="p" />
            </div>
        </div>
    </div>
</template>

<script setup>
import ProductCard from '../components/ProductCard.vue';

definePageMeta({
    layout: 'products',
})

 const { data : products } = await useFetch('https://fakestoreapi.com/products')

 useHead({
    title: 'Products',
    meta: [
        {
            name: 'description',
            content: 'This is the products page'
        }
    ]
})

</script>
