<template>
  <header>
    <h1>Hello Otrum</h1>
  </header>
</template>

<script>
import Button from "./Button.vue";
export default {
  name: 'Header',
  components: {Button},
}
</script>
<style>
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 20px;
  align-content: space-evenly;
}
</style>