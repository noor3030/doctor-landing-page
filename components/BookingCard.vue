<script lang="ts" setup>
const props = defineProps({
  name: {
    type: String,
    required: true,
  },
  description: {
    type: String,
    required: true,
  },
  icon: {
    type: String,
    required: true,
  },
});
</script>

<template>
  <div class="flex">
    <div
      class="flex justify-center content-center border-2 border-[#ffff] rounded-lg p-3 gap-x-16"
    >
      <div class="flex flex-col">
        <h1 class="text-2xl">{{ name }}</h1>
        <span class="text-xl"> {{ description }}</span>
      </div>
      <div
        class="flex justify-center content-center rounded-full bg-[#ffff] self-center p-2"
      >
        <img :src="icon" alt="" />
      </div>
    </div>
  </div>
</template>
