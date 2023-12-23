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
  <div class="flex gap-x-2">
    <div class="bg-[#00c8d5] w-fit p-2 rounded-full h-fit">
      <img :src="icon" alt="" class="w-10" />
    </div>

    <div class="flex flex-col ">
      <h1 class="text-2xl">{{ name }}</h1>
      <p class="text-[#646566] text-base lg:text-xl">{{ description }}</p>
    </div>
  </div>
</template>
