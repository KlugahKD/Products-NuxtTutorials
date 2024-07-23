<template>
    <div>
        <p> Product details for {{ id }}</p>
        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Veniam facere labore delectus, odio tempora asperiores repudiandae incidunt ipsam maiores totam sapiente illum amet esse nobis animi odit quod nesciunt similique!</p>
    
    </div>
</template>

<script setup>

const { id } = useRoute().params;

</script>

<style scoped>

</style>