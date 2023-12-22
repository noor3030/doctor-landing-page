<template>
  <div class="relative z-50">
    <nav
      class="py-4 px-16 bg-[#cefbfe] md:grid md:grid-cols-3 w-full fixed top-0 left-0 right-0 hidden"
    >
      <img src="../public/logos/logo.svg" class="w-16 h-16" />

      <div class="flex gap-x-2 text-xl self-center col-span-2">
        <a href="#home" class="hover:bg-white rounded-lg p-2"> الرئيسية</a>

        <a href="#treatment" class="hover:bg-white rounded-lg p-2">العلاجات</a>
        <a href="#about-us" class="hover:bg-white rounded-lg p-2">من نحن </a>
        <a href="#service" class="hover:bg-white rounded-lg p-2">الخدمات</a>

        <a href="#doctors" class="hover:bg-white rounded-lg p-2">الاطباء</a>
        <a href="#articles" class="hover:bg-white rounded-lg p-2">المدونات </a>
        <a href="contact-us" class="hover:bg-white rounded-lg p-2"
          >تواصل معنا</a
        >
      </div>
    </nav>
  </div>
  <div class="md:hidden">
    <div
      :class="open ? ' opacity-25' : 'opacity-100'"
      class="grid grid-cols-2 w-full py-4 px-5"
    >
      <button @click="tog()" class="text-black text-2xl font-bold w-fit">
        &#9776;
      </button>
      <img src="../public/logos/slogan.svg" alt="" class="w-3/4 self-center" />
    </div>
    <nav
      :class="open ? 'navbar-open' : 'navbar-close'"
      class="navbar w-64 absolute overflow-x-scroll bg-gray-50 top-0 h-screen"
    >
      <div class="flex pr-2 justify-end">
        <button @click="tog()" class="p-2 text-black text-xl font-bold">
          &#9747;
        </button>
      </div>

      <ul class="list-none text-black text-center flex flex-col gap-y-3">
        <li><h1 class="text-xl text-center font-bold">القائمة</h1></li>
        <li>
          <a href="#home" class="hover:bg-white rounded-lg p-2"> الرئيسية</a>
        </li>
        <li>
          <a href="#treatment" class="hover:bg-white rounded-lg p-2"
            >العلاجات</a
          >
        </li>
        <li>
          <a href="#about-us" class="hover:bg-white rounded-lg p-2">من نحن </a>
        </li>
        <li>
          <a href="#service" class="hover:bg-white rounded-lg p-2">الخدمات</a>
        </li>
        <li>
          <a href="#doctors" class="hover:bg-white rounded-lg p-2">الاطباء</a>
        </li>
        <li>
          <a href="#articles" class="hover:bg-white rounded-lg p-2"
            >المدونات
          </a>
        </li>
        <li>
          <a href="contact-us" class="hover:bg-white rounded-lg p-2"
            >تواصل معنا</a
          >
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
