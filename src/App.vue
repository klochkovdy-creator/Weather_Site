<script setup lang="ts">
const test = () => {
  alert("I was pressed!") 
}
</script>

<template>
  <h1>You did it!</h1>
  <button @click="test">Кнопка <button>
  <p>
    Visit <a href="https://vuejs.org/" target="_blank" rel="noopener">vuejs.org</a> to read the
    documentation
  </p>
</template>

<style scoped></style>
