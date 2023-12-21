<template>
  <div class="flex flex-col p-16" id="home">
    <div class="grid grid-cols-2">
      <div class="text-section justify-start content-start flex flex-col">
        <div class="text-5xl flex font-bold gap-x-4">
          <h1>ابحث عن</h1>
          <h1 class="text-[#00c3d3]">طبيبك</h1>
          <h1>&</h1>
          <h1>احجز موعدك</h1>
        </div>

        <p class="mt-10 text-2xl text-[#646566]">
          مع اكبر تطبيق لحجز المواعيد الطبية في العراق اضمن صحتك وصحة عائلتك مع
          تطبيق
        </p>
        <h1 class="text-4xl font-bold text-[#00c3d3] mt-2">CARE</h1>

        <div class="flex actions">
          <button
            class="text-white bg-gradient-to-r from-cyan-400 via-cyan-500 to-cyan-600 hover:bg-gradient-to-br focus:ring-4 focus:outline-none focus:ring-cyan-300 dark:focus:ring-cyan-800 rounded-lg text-3xl px-5 py-2 mt-10"
          >
            حمل التطبيق الان
          </button>
        </div>
      </div>
      <div
        class="image-section flex flex-col justify-start content-start h-fit"
      >
        <img
          src="../public/doctors-images/appbar-image.png"
          alt=""
          class="object-contain w-5/6 h-5/6"
        />
      </div>
    </div>
    <Booking></Booking>
  </div>
</template>
