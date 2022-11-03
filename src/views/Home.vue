<template>
    <div class="flex h-screen justify-center items-center">
      <div class="text-center">
        <Example />
        <br>
        <br>
        <h1>Home</h1>
        <router-link :to="'/about'">About Page</router-link>
      </div>
    </div>
</template>

<style lang="scss" scoped>

</style>

<script setup>
import Example from '@/components/Example.vue';
</script>