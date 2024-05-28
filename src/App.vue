<template>
  <div>
    <router-link to="/">Home</router-link>
    <router-link to="/about">About</router-link>
  </div>
</template>

<script setup>
import { ref } from "vue";

const name = ref("Mr.Sombat Buekeaw");
const age = 19;
</script>

<style lang="scss" scoped>
</style>