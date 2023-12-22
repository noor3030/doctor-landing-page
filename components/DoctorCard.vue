<script lang="ts" setup>
const props = defineProps({
  name: {
    type: String,
    required: true,
  },
  specialty: {
    type: String,
    required: true,
  },
  rating: {
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
  <div
    class="bg-[#ffff] flex flex-col justify-center content-center text-center p-5 rounded-lg  gap-y-4 self-center"
  >
    <img :src="image" class="self-center rounded-lg" />
  
    <h1 class="text-2xl font-bold text-[#0d1c3e]">{{ name }}</h1>
    <h1 class="text-xl text-[#0d1c3e]">{{ specialty }}</h1>
    <div class="flex justify-center content-center gap-x-1">
      <img width="24" height="24" src="https://img.icons8.com/sf-black-filled/24/00c8d5/star.png" alt="star"/>      <h1 class="text-xl text-[#00c8d5]">{{ rating }}</h1>
    </div>
    <button
      class="text-[#00c8d5] rounded-lg px-5 py-2 mt-5 w-fit self-center border border-[#00c8d5] hover:bg-[#00c8d5] hover:text-[#ffff] transition duration-500 ease-in-out] text-xl"
    >
      احجز موعدك الان
    </button>
  </div>
</template>
