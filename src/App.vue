<template>
  <main>
    <LetterA></LetterA>
  </main>
</template>

<script setup>
import LetterA from './components/LetterA.vue'
</script>

<style>
#app {
  display: grid;
  grid-template-columns: 1500px;
  grid-template-rows: 250px 250px;
  margin: 16px;
  margin-right: 0;
}
main {
  display: grid;
  grid-template-columns: repeat(10, 150px);
}
.top,
.center,
.bottom,
.left,
.right {
  background-color: red;
}
.a,
.b,
.e,
.h,
.i,
.j,
.n,
.o,
.s,
.t {
  width: 120px;
  height: 200px;
  display: grid;
  grid-template-columns: repeat(5, 20%);
  grid-template-rows: repeat(5, 20%);
}
</style>
