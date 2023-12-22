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
          <img width="24" height="24" src="https://img.icons8.com/sf-black-filled/24/0d1c3e/star.png" alt="star"/>
            <p class="text-lg font-bold">{{ rate }}</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
