<script setup>
//search Movie
const searchError = ref(false);
const searchMovie = (searchInput) =>{

if(searchInput === ""){
    searchError.value = true;
}
if (searchInput !== ""){;
    // console.log(searchInput)
    //Movie Search code here
    searchError.value = false;
}
};
//fetch movie details
const movieid = ref(123);
const title = ref("Batman");
const date = ref("20-01-2024");
const poster = ref("https://www.themoviedb.org/t/p/w600_and_h900_bestv2/74xTEgt7R36Fpooo50r9T25onhq.jpg");
</script>

<template>
    <div class="container mx-auto">
        <SearchBar @search-movie="searchMovie" :searchError="searchError" />
        <div class="grid md:grid-cols-4 sm:grid-cols-1 justify-items-center bg-cyan-50">
            <div v-for="n in 8">
                <MovieCard :title="title" :date="date" :movieid="movieid" :poster="poster"/>
            </div>
        </div>
    </div>
</template>