<script setup>
import Header from "./components/Header.vue";
</script>

<template>
  <div class="container">
  <Header/>
  </div>
  <main>

  </main>
</template>

<style>
@import './assets/base.css';

#app {
  max-width: 1280px;
  margin: 0 auto;
  padding: 2rem;

  font-weight: normal;
}*/

header {
  line-height: 1.5;
}

.container {
  max-width: 500px;
  margin: 30px auto;
  overflow: auto;
  min-height: 300px;
  border: 1px solid steelblue;
  padding: 30px;
  border-radius: 5px;
}

/*a,
.green {
  text-decoration: none;
  color: hsla(160, 100%, 37%, 1);
  transition: 0.4s;
}*/

@media (hover: hover) {
  a:hover {
    background-color: hsla(160, 100%, 37%, 0.2);
  }
}

@media (min-width: 1024px) {
  body {
    display: flex;
    place-items: center;
  }

  header {
    display: flex;
    place-items: center;
    align-self: center;
    padding-right: calc(var(--section-gap) / 2);
  }

/*  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }*/

}
</style>
