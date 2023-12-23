<template>
  <div
    class="md:flex md:p-16 p-6 lg:p-16 justify-between content-between"
    id="about-us"
  >
    <div class="text-section flex flex-col gap-y-3 ">
      <h1 class="text-[#00c8d5] md:text-start text-center text-3xl lg:text-4xl">من نحن</h1>
      <div class="md:flex gap-x-3 font-bold text-3xl lg:text-5xl">
        <h1 class="text-[#0d1c3e]">حلول</h1>
        <h1 class="text-[#00c8d5]">الرعاية الصحية</h1>
        <h1 class="text-[#0d1c3e]">الحديثة</h1>
      </div>
      <p class="md:text-xl text-[#646566]">
        من خلال تطبيقنا يمكنك العثور على افضل الاطباء والعيادات والمجمعات الطبية
        لتضمن لك الرعاية الصحية اللازمة والمناسبة لك ولعائلتك وسرعة الوصول اليها
        والحجز المباشر الالكتروني
      </p>

      <div class="flex flex-col pt-8 gap-y-5">
        <AboutUsIcons
          name="الاطباء"
          description="  افضل الاطباء والاخصائيين  في مختلف التخصصات"
          icon="../icons/doctor.svg"
        />
        <AboutUsIcons
          name="العيادات"
          description="افضل العيادات والمراكز الطبية في مختلف التخصص"
          icon="../icons/clinic.svg"
        />
        <AboutUsIcons
          name="المجمعات الطبية"
          description="مجمعات طبية متكاملة تضم افضل الاطباء والعيادات"
          icon="../icons/medical-complexes.svg"
        />
        <AboutUsIcons
          name="المختبرات"
          description="مختبرات متخصصة ومجهزة بأحدث الاجهزة والتقنيات"
          icon="../icons/needle.svg"
        />
      </div>
    </div>
    <div
      class="img-section flex md:justify-end md:content-end justify-center content-center"
    >
      <img
        src="../public/doctors-images/about-image.png"
        alt="about-us"
        class="w-3/4 md:w-full h-3/4 md:h-full object-contain"
      />
    </div>
  </div>
</template>
