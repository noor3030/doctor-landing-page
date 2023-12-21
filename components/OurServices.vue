<template>
  <div
    class="relative overflow-hidden rounded-lg bg-cover bg-no-repeat p-16 h-fit"
    style="background-image: url(../doctors-images/background.png)"
    id="service"
  >
    <h1 class="text-5xl text-[#00c8d5] text-center">الخدمات</h1>
    <div class="flex text-5xl gap-x-3 font-bold text-center justify-center">
      <h1 class="text-[#0d1c3e]">خدماتنا</h1>
      <h1 class="text-[#00c8d5]">عالية</h1>
      <h1 class="text-[#0d1c3e]">الجودة</h1>
    </div>

    <div class="flex gap-x-10 justify-center content-center mt-10">
      <ServiceCard
        name="الحجز الالكتروني"
        description="احجز موعدك الان بكل سهولة ويسر"
        icon="https://img.icons8.com/external-flatart-icons-outline-flatarticons/64/FFFFFF/external-phone-modern-business-and-business-essentials-flatart-icons-outline-flatarticons.png"
      />
      <ServiceCard
        name="الوصول السريع"
        description="اعثر على اقرب العيادات والمجمعات الطبية لك"
        icon="https://img.icons8.com/ios/50/FFFFFF/calling.png"
      />
      <ServiceCard
        name="الرعاية الصحية"
        description="احصل على الرعاية الصحية اللازمة لك ولعائلتك"
        icon="https://img.icons8.com/ios/50/FFFFFF/trust--v1.png"
      />
      <ServiceCard
        name="التواصل المباشر"
        description="تواصل مع الاطباء والعيادات بكل سهولة"
        icon="https://img.icons8.com/external-kmg-design-detailed-outline-kmg-design/64/FFFFFF/external-video-call-work-from-home-kmg-design-detailed-outline-kmg-design.png"
      />
      <ServiceCard
        name="التقييم"
        description="قيم الاطباء والعيادات وشارك تجربتك مع الاخرين"
        icon="https://img.icons8.com/ios/50/FFFFFF/popular-woman.png"
      />
    </div>

    <div class="flex gap-x-6 justify-center content-center mt-10">
      <ServiceCard
        name="التنبيهات"
        description="تلقي التنبيهات والاشعارات بكل ما هو جديد"
        icon="https://img.icons8.com/ios/50/FFFFFF/alarm--v1.png"
      />
      <ServiceCard
        name="المفضلة"
        description="اضف الاطباء والعيادات المفضلة لك"
        icon="https://img.icons8.com/material-rounded/24/FFFFFF/filled-like.png"
      />

      <ServiceCard
        name="الملف الشخصي"
        description="تعرف على ملفك الشخصي وتاريخك الصحي"
        icon="https://img.icons8.com/material-outlined/24/FFFFFF/user-male-circle.png"
      />
      <ServiceCard
        name="المزيد"
        description="اكتشف المزيد من الخدمات والمميزات"
        icon="https://img.icons8.com/ios/50/FFFFFF/more.png"
      />
      <ServiceCard
        name="التسجيل"
        description="سجل الان واستفد من كل مميزات التطبيق"
        icon="https://img.icons8.com/material-outlined/24/FFFFFF/task.png"
      />
    </div>
  </div>
</template>
