<script setup>
import HeaderVue from './components/Header.vue';
import MovieCard from './components/MovieCard.vue';
import Footer from './components/Footer.vue';
</script>

<template>

  <main>
    <HeaderVue/>
    <div class="all">
      <MovieCard/>
      <MovieCard/>
      <MovieCard/>
      <MovieCard/>
      <MovieCard/>
      <MovieCard/>
      <MovieCard/>
      <MovieCard/>
    </div>
    <Footer/>
  </main>
</template>

<style>

.all {
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    flex-flow: wrap;
    align-items: center;
    flex: 1 0 calc(25% - 10px);
    justify-content: center;
}

main {
  height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}

</style>
