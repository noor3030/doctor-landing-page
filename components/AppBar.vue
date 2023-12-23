<template>
  <div class="flex flex-col md:p-8 md:mt-20 p-6 lg:p-16" id="home">
    <div class="md:grid md:grid-cols-2">
      <div
        class="text-section justify-start content-start text-start flex flex-col gap-y-5"
      >
        <div class="font-bold gap-x-2 text-xl hidden lg:flex lg:text-4xl">
          <h1>ابحث عن</h1>
          <h1 class="text-[#00c3d3]">طبيبك</h1>
          <h1>&</h1>
          <h1>احجز موعدك</h1>
        </div>
        <div class="lg:hidden text-5xl font-bold flex flex-col gap-y-4">
          <h1 class="text-[#00c3d3]">ابحث عن طبيبك</h1>
          <h1>واحجز موعدك</h1>
        </div>
        <p class="lg:text-xl text-[#646566]">
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
          <a href="" class=" w-1/2 lg:w-1/3">
            <img src="../public/app-store.svg" alt=""
          /></a>
          <a href="" class=" w-1/2 lg:w-1/3">
            <img src="../public/google-play.svg" alt="" />
          </a>
        </div>
      </div>
      <div class="image-section h-fit flex justify-center items-center pt-16">
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
