<template>
    <div>
        <h2>About</h2>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Doloribus, modi quos? Facilis alias vero animi obcaecati doloribus sint mollitia veritatis?</p>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Doloribus, modi quos? Facilis alias vero animi obcaecati doloribus sint mollitia veritatis?</p>
        <div>{{ data }}</div>
    </div>
</template>

<script setup>
    const {data} = await useFetch('/api/currency/GBP');
</script>

<style scoped>
    h2 {
        margin: 0 0 20px 0;
        font-size: 36px;
    }
    p {
        margin: 20px 0;
    }

</style>