<script lang="ts" setup>
const props = defineProps({
  specialization: {
    type: String,
    required: true,
  },
  typeOfTreatment: {
    type: String,
    required: true,
  },
  rate: {
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
    class="relative overflow-hidden rounded-lg bg-cover bg-no-repeat p-5 text-white self-center"
    :style="`background-image: url(${image}) ; height:300px ; width:300px `"
  >
    <div class="bg-[#0d1c3e] w-fit text-lg p-2 rounded-lg">
      {{ specialization }}
    </div>
    <div
      class="absolute top-0 left-0 w-full h-full bg-black bg-opacity-50 justify-center items-center opacity-0 hover:opacity-100 transition-all duration-500 flex"
    >
      <div class="text-center">
        <h1 class="text-2xl font-bold">{{ typeOfTreatment }}</h1>
        <div class="flex justify-center items-center">
          <div
            class="w-fit p-2 rounded-xl bg-[#00c8d5] text-center text-[#0d1c3e] flex gap-x-1 mt-5"
          >
            <svg
              class="w-6 h-6"
              aria-hidden="true"
              xmlns="http://www.w3.org/2000/svg"
              fill="currentColor"
              viewBox="0 0 22 20"
            >
              <path
                d="M20.924 7.625a1.523 1.523 0 0 0-1.238-1.044l-5.051-.734-2.259-4.577a1.534 1.534 0 0 0-2.752 0L7.365 5.847l-5.051.734A1.535 1.535 0 0 0 1.463 9.2l3.656 3.563-.863 5.031a1.532 1.532 0 0 0 2.226 1.616L11 17.033l4.518 2.375a1.534 1.534 0 0 0 2.226-1.617l-.863-5.03L20.537 9.2a1.523 1.523 0 0 0 .387-1.575Z"
              />
            </svg>
            <p class="text-lg font-bold">{{ rate }}</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
