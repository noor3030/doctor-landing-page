<template>
  <div
    class="bg-[#00c8d5] md:py-10 text-[#ffff] w-full flex flex-col md:gap-y-14 rounded-lg gap-y-6 p-6"
  >
    <h1 class="md:text-4xl  text-3xl font-bold text-center">أكد حجزك الان</h1>

    <div class="flex flex-col gap-y-6 content-center justify-center">
      <BookingCard
        name="الهاتف"
        description="07000000000"
        icon="https://img.icons8.com/ios/32/081839/phone--v1.png"
      />
      <BookingCard
        name="البريد الالكتروني"
        description="care@gmail.com"
        icon="https://img.icons8.com/ios/32/081839/email.png"
      />
      <BookingCard
        name="التاريخ"
        description=" 20/10/2021"
        icon="https://img.icons8.com/ios/32/081839/calendar--v1.png"
      />
      <button
        class="bg-white rounded-lg text-2xl text-[#081839] px-6 hover:bg-transparent hover:text-white border-2 border-white"
      >
        <h1>احجز الان</h1>
      </button>
    </div>

    <div class="flex gap-x-5 content-center justify-center">
      <div class="flex md:-space-x-8 -space-x-4 rtl:space-x-reverse">
        <div v-for="(item, index) in 6" :key="index">
          <img
            width="60"
            height="60"
            src="https://img.icons8.com/office/80/circled-user-male-skin-type-1-2.png"
            alt="circled-user-male-skin-type-1-2"
          />
        </div>
      </div>
      <p class="text-xl self-center ">
        <b>+300</b>
        تأكيد حجز المواعيد لهذا الأسبوع
      </p>
    </div>
  </div>
</template>
