<template>
    <div>
     <h2>About</h2>
     <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sapiente, fugit totam libero hic voluptate porro cupiditate quia quam nam reiciendis unde culpa repudiandae molestias praesentium, nesciunt ipsam temporibus dolor itaque.</p>
     <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sapiente, fugit totam libero hic voluptate porro cupiditate quia quam nam reiciendis unde culpa repudiandae molestias praesentium, nesciunt ipsam temporibus dolor itaque.</p>
     <div> {{ data }} </div>
    </div>
</template>

<script setup>
  const { data } = await useFetch('/api/apiRoutes');

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