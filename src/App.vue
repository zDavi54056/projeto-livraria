<script setup>
import HeaderComp from "@/components/template/HeaderComp.vue";
import RodapeComp from "@/components/template/RodapeComp.vue";
</script>

<template>
  <HeaderComp />
  <main>
    <RouterView />
  </main>
  <RodapeComp />
</template>

<style>
@import "@/assets/base.css";

#app {
  background-color: white;
  max-width: 1280px;
  margin: 0 auto;
  font-weight: normal;
  height: 100vh;
}

a {
  color: inherit;
  text-decoration: none;
}

main {
  height: 80%;
}
</style>
