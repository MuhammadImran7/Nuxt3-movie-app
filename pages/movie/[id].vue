<template>
<div>
    <MovieDetail :title="title" :date="date" :poster="poster" :revenue="revenue" :overview="overview"/>
</div>
</template>
<script setup>
definePageMeta({
    layout : 'custom'
});
const title = ref("Batman");
const date = ref("20-01-2024");
const poster = ref("https://www.themoviedb.org/t/p/w600_and_h900_bestv2/74xTEgt7R36Fpooo50r9T25onhq.jpg");
const revenue = ref(454545463);
const overview = ref( " Lorem ipsum dolor, sit amet consectetur adipisicing elit. Veniam aspernatur ipsa offici hdfhdfgdfgdfgdfgdsfgdfgdfgdfgdfg " );
</script>