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
  <div
    class="self-center rounded-lg flex flex-col justify-center content-center items-center gap-y-2 bg-white p-5 hover:bg-[#00c8d5] hover:text-white transition-all w-96"
  >
    <div class="bg-[#00c8d5] rounded-full p-3 w-fit h-fit">
      <img :src="icon" alt="icon" class="w-12 h-12" />
    </div>

    <h1 class="font-bold text-2xl">{{ name }}</h1>
    <p class="text-xl line-clamp-1">
      {{ description }}
    </p>
  </div>
</template>
