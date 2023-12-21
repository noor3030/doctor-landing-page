<template>
  <div class="bg-[#00c8d5] py-10 text-[#ffff] w-full flex flex-col gap-y-5">
    <h1 class="text-4xl font-bold text-center">أكد حجزك الان</h1>

    <div class="flex gap-x-12 content-center justify-center">
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
        description="السبت 20/10/2021"
        icon="https://img.icons8.com/ios/32/081839/calendar--v1.png"
      />
      <button
        class="bg-white rounded-lg text-2xl text-[#081839] px-6 hover:bg-transparent hover:text-white border-2 border-white"
      >
        <h1>احجز الان</h1>
      </button>
    </div>

    <div class="flex gap-x-5 content-center justify-center">
      <div class="flex -space-x-8 rtl:space-x-reverse mt-7">
        <div v-for="(item, index) in 10" :key="index">
          <img
            width="60"
            height="60"
            src="https://img.icons8.com/office/80/circled-user-male-skin-type-1-2.png"
            alt="circled-user-male-skin-type-1-2"
          />
        </div>
      </div>
      <p class="text-xl self-center mt-5">
        <b>+300</b>
        تأكيد حجز المواعيد لهذا الأسبوع
      </p>
    </div>
  </div>
</template>
