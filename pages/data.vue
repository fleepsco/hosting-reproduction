<template>
    <h1>Some data are fetching</h1>
    {{ data }}
</template>

<script setup lang="ts">
const { data } = await useFetch('https://cat-fact.herokuapp.com/facts');
</script>
