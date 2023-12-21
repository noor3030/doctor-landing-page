<template>
  <div class="flex flex-col p-16 mt-20" id="home">
    <div class="grid grid-cols-2">
      <div
        class="text-section justify-start content-start flex flex-col gap-y-10"
      >
        <div class="text-5xl flex font-bold gap-x-4">
          <h1>ابحث عن</h1>
          <h1 class="text-[#00c3d3]">طبيبك</h1>
          <h1>&</h1>
          <h1>احجز موعدك</h1>
        </div>

        <p class="text-2xl text-[#646566] w-2/3">
          تطبيقنا الجديد سيحدث ثورة كبيرة في تجربة الرعاية الصحية في العراق!
          يتضمن التطبيق معلومات شاملة عن الأطباء والإختصاصات، وتقييمات المرضى
          تجعل من اختيار الأطباء الأمثل أسهل، والحجز عبر التطبيق والاستشارات على
          الانترنت يجعل الطب أكثر قربًا وسهولة لجميع المرضى. كما يتيح الملفات
          الشخصية للأطباء عرض معلومات عن عيادتهم وموقعهم على الخريطة، فإن هذا
          التطبيق سوف يوفر للمستخدمين تجربة مثالية للرعاية الصحية. بالإضافة إلى
          ذلك، فإن مقالات وأخبار الموقع ومعلومات طبية مفيدة تجعل التطبيق مرجعًا
          مفيدًا لصحة الجميع. احصل على تطبيقنا الآن وجرب التجربة الطبية المتميزة
          المتوفرة حصريا داخل العراق!
        </p>

        <div class="flex actions gap-x-4">
          <a href="" class="w-1/4">
            <img src="../public/app-store.svg" alt=""
          /></a>
          <a href="" class="w-1/4">
            <img src="../public/google-play.svg" alt="" />
          </a>
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
