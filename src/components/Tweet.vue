<template>
  <div className="tweet">
    <ProfileImage :image="image" />

    <div className="body">
      <div className="top">
        <User :name="name" :handle="handle" />
        <Timestamp :timestamp="timestamp" />
      </div>

      <Message :message="message" />
      <Actions />
    </div>

    <i class="fas fa-ellipsis-h"></i>
  </div>
</template>



<script setup>
import { ref } from 'vue'

import Actions from './Actions.vue';
import Message from './Message.vue';
import ProfileImage from './ProfileImage.vue';
import Timestamp from './Timestamp.vue';
import User from './User.vue';
const props = defineProps(["message",  "image", "timestamp", "name", "handle" ]);

</script>


<style scoped>
a {
  color: #42b983;
}
</style>
