<template>
    <img
      src={{image}}
      className="profile"
      alt="profile"
    />
</template>

<script setup>
import { ref } from 'vue'
const props = defineProps([ "image"]);
</script>

<style lang="scss" scoped>

</style>