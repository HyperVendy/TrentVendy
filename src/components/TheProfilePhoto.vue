<script setup lang="ts">
import photo from '~/assets/me.jpg'
</script>

<template>
  <img :src="photo" class="avatar">
</template>

<style>
.avatar {
  border-radius: 50%;
  display: block;
  margin-left: auto;
  margin-right: auto;
  box-shadow: 0 4px 8px 0 rgb(0 0 0 / 20%), 0 6px 20px 0 rgb(0 0 0 / 19%);
}

.avatar:hover {
  box-shadow: 0 4px 8px 0 rgba(41, 169, 255, 40%), 0 6px 20px 0 rgb(41, 169, 255, 30%);
}
</style>
