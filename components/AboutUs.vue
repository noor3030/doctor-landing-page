<template>
  <div class="flex p-16 justify-between content-between">
    <div class="text-section flex flex-col gap-y-3">
      <h1 class="text-5xl text-[#00c8d5]">من نحن</h1>
      <div class="flex text-5xl gap-x-3 font-bold">
        <h1 class="text-[#0d1c3e]">حلول</h1>
        <h1 class="text-[#00c8d5]">الرعاية الصحية</h1>
        <h1 class="text-[#0d1c3e]">الحديثة</h1>
      </div>
      <p class="text-xl text-[#646566]">
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
    <div class="img-section">
      <img
        src="../public/doctors-images/about-image.png"
        alt="about-us"
        class="w-3/4"
      />
    </div>
  </div>
</template>
