<template>
      <span className="user">
          <span className="name">{{name}}</span>
          <span className="handle">{{handle}}</span>
        </span>
</template>

<script setup>
import { ref } from 'vue'
  const props = defineProps(["name", "handle" ]);
</script>

