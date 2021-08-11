<template>
  <h2>TypeScript</h2>
  <TsHelloWorld />
  <hr>
  <h2>Pug</h2>
  <PugHelloWorld />
  <hr>
  <h2>Pug + TypeScript</h2>
  <Problem />
  <hr>
</template>

<script setup lang="ts">
import TsHelloWorld from './components/TypescriptHelloWorld.vue';
import PugHelloWorld from './components/PugHelloWorld.vue';
import Problem from './components/PugAndTypescriptHelloWorld.vue';
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
