<template>
     <p className="message">
        {{message}}
      </p>
</template>

<script setup>
import { ref } from 'vue'
const props = defineProps([ "message"]);
</script>

<style lang="scss" scoped>

</style>