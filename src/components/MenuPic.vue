<script setup>
import { computed } from 'vue'
const props = defineProps(['textTitle', 'imgPath'])
console.log(props.textTitle)

const getImagePath = (imgPath) => {
  return `/src/assets/${imgPath}`;
};

const content = computed(() => `"${props.textTitle}"`)
</script>

<template>
  <div class="flex overflow-hidden w-full aspect-[1.8/1]">
    <img class="w-full" :src="getImagePath(imgPath)" :alt="textTitle" />
  </div>
</template>

<style scoped>
div::before {
  display: flex;
  justify-content: center;
  align-items: center;
  color: white;
  position: absolute;
  width: 100%;
  aspect-ratio: 1.6/1;
  content: v-bind(content);
  font-size: 2.5rem;
  font-weight: 900;
}
</style>