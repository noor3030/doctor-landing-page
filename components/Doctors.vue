<template>
  <div
    class="relative overflow-hidden rounded-lg bg-cover bg-no-repeat p-16 mt-16"
    style="background-image: url(../doctors-images/background.png)"
    id="doctors"
  >
    <h1 class="text-5xl text-[#00c8d5] text-center">الاطباء</h1>
    <div class="flex text-5xl gap-x-3 font-bold text-center justify-center">
      <h1 class="text-[#0d1c3e]">الاطباء</h1>
      <h1 class="text-[#00c8d5]">الاكثر</h1>
      <h1 class="text-[#0d1c3e]">تقييما</h1>
    </div>

    <div class="flex justify-center gap-x-5 gap-y-5 mt-10">
      <DoctorCard
        name="د. محمد عبد الرحمن"
        specialty="اخصائي الجراحة العامة"
        rating="4.5"
        image="../doctors-images/doctor1.png"
      />
      <DoctorCard
        name="د. سهى حميد  "
        specialty="اخصائية اسنان "
        rating="4.5"
        image="../doctors-images/doctor2.png"
      />
      <DoctorCard
        name="د. رحيم محمد"
        specialty="اخصائي اطفال "
        rating="4.5"
        image="../doctors-images/doctor3.png"
      />
      <DoctorCard
        name="د.   علي وليد"
        specialty="اخصائي باطنية"
        rating="4.5"
        image="../doctors-images/doctor4.png"
      />
      <DoctorCard
        name="د. احمد عبد السلام"
        specialty="اخصائي  العيون"
        rating="4.5"
        image="../doctors-images/doctor5.png"
      />
    </div>
  </div>
</template>
