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
  date: {
    type: String,
    required: true,
  },
  image: {
    type: String,
    required: true,
  },
});
</script>

<template>
  <div class="bg-[#ffff] flex flex-col p-5 rounded-lg md:w-96 shadow-lg gap-y-4 self-center">
    <img
      :src="image"
      class="self-center rounded-lg"
      style="height: 250px; width: 300px"
    />
    <div class="flex gap-x-2">
      <h1 class="text-xl text-[#00c8d5]">{{ date }}</h1>

      <img width="28" height="28" src="https://img.icons8.com/ios/28/00c8d5/calendar--v1.png" alt="calendar--v1"/>
    </div>

    <h1 class="text-2xl font-bold text-[#0d1c3e]">{{ name }}</h1>
    <h1 class="text-xl text-[#646566] line-clamp-3">{{ description }}</h1>

    <button
      class="text-[#00c8d5] rounded-lg px-5 py-2 mt-5 w-fit self-center border border-[#00c8d5] hover:bg-[#00c8d5] hover:text-[#ffff] transition duration-500 ease-in-out] text-xl"
    >
      قراة المزيد
    </button>
  </div>
</template>
