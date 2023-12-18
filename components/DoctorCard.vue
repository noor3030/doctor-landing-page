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
    class="bg-[#ffff] flex flex-col justify-center content-center text-center p-5 rounded-lg  gap-y-4"
  >
    <img :src="image" class="self-center rounded-lg" />
  
    <h1 class="text-2xl font-bold text-[#0d1c3e]">{{ name }}</h1>
    <h1 class="text-xl text-[#0d1c3e]">{{ specialty }}</h1>
    <div class="flex justify-center content-center gap-x-1">
      <svg
        class="w-6 h-6 text-[#00c8d5] dark:text-white"
        aria-hidden="true"
        xmlns="http://www.w3.org/2000/svg"
        fill="currentColor"
        viewBox="0 0 22 20"
      >
        <path
          d="M20.924 7.625a1.523 1.523 0 0 0-1.238-1.044l-5.051-.734-2.259-4.577a1.534 1.534 0 0 0-2.752 0L7.365 5.847l-5.051.734A1.535 1.535 0 0 0 1.463 9.2l3.656 3.563-.863 5.031a1.532 1.532 0 0 0 2.226 1.616L11 17.033l4.518 2.375a1.534 1.534 0 0 0 2.226-1.617l-.863-5.03L20.537 9.2a1.523 1.523 0 0 0 .387-1.575Z"
        />
      </svg>
      <h1 class="text-xl text-[#00c8d5]">{{ rating }}</h1>
    </div>
    <button
      class="text-[#00c8d5] rounded-lg px-5 py-2 mt-5 w-fit self-center border border-[#00c8d5] hover:bg-[#00c8d5] hover:text-[#ffff] transition duration-500 ease-in-out] text-xl"
    >
      احجز موعدك الان
    </button>
  </div>
</template>
