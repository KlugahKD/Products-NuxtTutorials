<template>
    <div>
        <header>
            <h1>My Nuxt App</h1>
            <nav>
                <NuxtLink>My Nuxt App</NuxtLink>
                <ul>
                    <li><nuxt-link to="/">Home</nuxt-link></li>
                    <li><nuxt-link to="/about">About</nuxt-link></li>
                    <li><nuxt-link to="/products">Products</nuxt-link></li>
                </ul>
            </nav>

        </header>
     <h2>Home</h2>
     <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sapiente, fugit totam libero hic voluptate porro cupiditate quia quam nam reiciendis unde culpa repudiandae molestias praesentium, nesciunt ipsam temporibus dolor itaque.</p>
     <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sapiente, fugit totam libero hic voluptate porro cupiditate quia quam nam reiciendis unde culpa repudiandae molestias praesentium, nesciunt ipsam temporibus dolor itaque.</p>
    </div>
</template>

<script setup>

</script>

<style scoped>
h2 {
    margin-bottom: 20px;
    font-size: 30px;
}
p {
    font-size: 18px;
    margin: 20px 0;
}
</style>