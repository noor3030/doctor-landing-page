<template>
  <div class="p-16 text-center bg-[#f1fbfc]  flex flex-col gap-y-10">
    <h1
      class="p-2 text-5xl font-bold bg-gradient-to-l from-[#0d1c3e] from-10% to-[#00c8d5] to-90% bg-clip-text text-transparent"
    >
      العلاجات الاكثر شعبية لدينا
    </h1>

    <div class="flex justify-between content-between">
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
