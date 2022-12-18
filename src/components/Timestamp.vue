<template>
    <span className="timestamp">{{timestamp}}</span>
</template>

<script setup>
import { ref } from 'vue'
const props = defineProps([ "timestamp"]);
</script>

<style lang="scss" scoped>

</style>