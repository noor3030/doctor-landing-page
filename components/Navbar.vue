<template>
  <div class="relative z-50">
    <nav
      class="py-4 px-8 bg-[#cefbfe] md:flex justify-between w-full fixed top-0 left-0 right-0 hidden lg:px-16"
    >
      <img src="../public/logos/logo.svg" class="w-12 h-12 xl:w-16 xl:h-16" />

      <div class="flex self-center text-center lg:text-xl">
        <a
          href="#home"
          class="hover:bg-[#00c8d5] hover:text-white rounded-lg p-2"
        >
          الرئيسية</a
        >

        <a
          href="#treatment"
          class="hover:bg-[#00c8d5] hover:text-white rounded-lg p-2"
          >العلاجات</a
        >
        <a
          href="#about-us"
          class="hover:bg-[#00c8d5] hover:text-white rounded-lg p-2"
          >من نحن
        </a>
        <a
          href="#service"
          class="hover:bg-[#00c8d5] hover:text-white rounded-lg p-2"
          >الخدمات</a
        >

        <a
          href="#doctors"
          class="hover:bg-[#00c8d5] hover:text-white rounded-lg p-2"
          >الاطباء</a
        >
        <a
          href="#articles"
          class="hover:bg-[#00c8d5] hover:text-white rounded-lg p-2"
          >المدونات
        </a>
        <a
          href="contact-us"
          class="hover:bg-[#00c8d5] hover:text-white rounded-lg p-2"
          >تواصل معنا</a
        >
      </div>

      <div class="flex content-center items-center gap-x-2">
        <a href="https://www.facebook.com/iq.care1">
          <img
            width="32"
            height="32"
            src="https://img.icons8.com/ios-glyphs/32/00c8d5/facebook-new.png"
            alt="facebook-new"
        /></a>
        <a href="https://www.instagram.com/iq.care"
          ><img
            width="32"
            height="32"
            src="https://img.icons8.com/ios-glyphs/32/00c8d5/instagram-new.png"
            alt="instagram-new"
        /></a>
        <a href="https://www.tiktok.com/@iq.care">
          <img
            width="32"
            height="32"
            src="https://img.icons8.com/ios-filled/32/00c8d5/tiktok--v1.png"
            alt="tiktok--v1"
        /></a>

        <a href="https://wa.me/+9647815452962">
          <img
            width="32"
            height="32"
            src="https://img.icons8.com/ios-filled/32/00c8d5/whatsapp--v1.png"
            alt="whatsapp--v1"
        /></a>
      </div>
    </nav>
  </div>

  <div class="md:hidden">
    <div
      :class="open ? ' opacity-25' : 'opacity-100'"
      class="flex w-full py-4 px-6 bg-[#cefbfe] justify-between"
    >
      <img src="../public/logos/slogan.svg" alt="" class="w-1/4" />

      <button @click="tog()" class="font-bold text-xl text-[#0d1c3e]">
        &#9776;
      </button>
    </div>
    <nav
      :class="open ? 'navbar-open' : 'navbar-close'"
      class="navbar w-full absolute overflow-x-scroll bg-[#cefbfe] top-0 h-screen"
    >
      <div class="flex p-2">
        <button @click="tog()" class="p-2 text-xl font-bold">&#9747;</button>
      </div>

      <ul class="list-none text-center flex flex-col gap-y-3">
        <li><h1 class="text-xl text-center font-bold">القائمة</h1></li>
        <li>
          <a href="#home"> الرئيسية</a>
        </li>
        <li>
          <a href="#treatment">العلاجات</a>
        </li>
        <li>
          <a href="#about-us">من نحن </a>
        </li>
        <li>
          <a href="#service">الخدمات</a>
        </li>
        <li>
          <a href="#doctors">الاطباء</a>
        </li>
        <li>
          <a href="#articles">المدونات </a>
        </li>
        <li>
          <a href="contact-us">تواصل معنا</a>
        </li>

        <li class="flex justify-center gap-x-2">
          <a href="https://www.facebook.com/iq.care1">
            <img
              width="32"
              height="32"
              src="https://img.icons8.com/ios-glyphs/32/00c8d5/facebook-new.png"
              alt="facebook-new"
          /></a>
          <a href="https://www.instagram.com/iq.care"
            ><img
              width="32"
              height="32"
              src="https://img.icons8.com/ios-glyphs/32/00c8d5/instagram-new.png"
              alt="instagram-new"
          /></a>
          <a href="https://www.tiktok.com/@iq.care">
            <img
              width="32"
              height="32"
              src="https://img.icons8.com/ios-filled/32/00c8d5/tiktok--v1.png"
              alt="tiktok--v1"
          /></a>

          <a href="https://wa.me/+9647815452962">
            <img
              width="32"
              height="32"
              src="https://img.icons8.com/ios-filled/32/00c8d5/whatsapp--v1.png"
              alt="whatsapp--v1"
          /></a>
        </li>
      </ul>
    </nav>
  </div>
</template>
<script>
export default {
  name: "App",
  data() {
    return {
      open: false,
    };
  },

  methods: {
    tog() {
      this.open = !this.open;
    },
  },
};
</script>

<style>
.navbar {
  transition: all 330ms ease-out;
}

.navbar-open {
  transform: translateX(0%);
}
.navbar-close {
  transform: translateX(-100%);
}
</style>
