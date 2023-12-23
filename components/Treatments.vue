<template>
  <div
    class="relative overflow-hidden rounded-lg bg-cover bg-no-repeat md:p-16 h-fit p-6 lg:p-16"
    style="background-image: url(../doctors-images/background.png)"
    id="treatment"
  >
    <div
      class="md:flex-row flex flex-col md:text-5xl text-3xl gap-x-3 font-bold text-center justify-center md:mb-16 pb-5"
    >
      <h1 class="text-[#0d1c3e]">العلاجات</h1>
      <h1 class="text-[#00c8d5]">الاكثر شعبية</h1>
      <h1 class="text-[#0d1c3e]">لدينا</h1>
    </div>

    <div class="flex flex-wrap gap-2 justify-center content-center">
      <TreatmentCard
        specialization="قلع الاسنان"
        typeOfTreatment="علاج الاسنان"
        rate="5"
        image="../doctors-images/treatment1.jpg"
      />
      <TreatmentCard
        specialization="امراض القلب "
        typeOfTreatment="جراحة صمامات القلب "
        rate="5"
        image="../doctors-images/treatment2.jpg"
      />
      <TreatmentCard
        specialization="العناية بالبشرة"
        typeOfTreatment="افضل تقنيات العناية بالبشرة"
        rate="5"
        image="../doctors-images/treatment3.jpg"
      />
      <TreatmentCard
        specialization="طب الاطفال"
        typeOfTreatment=" عيادات خاصة لمعالجة الاطفال  "
        rate="5"
        image="../doctors-images/treatment4.jpg"
      />
      <TreatmentCard
        specialization="عيادات العيون"
        typeOfTreatment="احدث الاجهزة لفحص النظر "
        rate="5"
        image="../doctors-images/treatment5.jpg"
      />
    </div>
  </div>
</template>
