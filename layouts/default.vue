<template>
  <div>
    <div class="w-full bg-yellow-500 z-10 shadow-xl py-2 fixed top-0">
      <div class="lg:hidden block">
        <div class="flex flex-row mx-3 justify-between">
          <button @click="toggle = true">
            <i class="fas fa-bars text-black fa-2x"></i>
          </button>
          <nuxt-link to="#">
            <i class="fab fa-pied-piper text-black fa-2x"></i>
          </nuxt-link>
          <nuxt-link to="#">
            <i class="far fa-user-circle text-black fa-2x"></i>
          </nuxt-link>
        </div>
        <div class="bg-white flex flex-col w-96">
          <button
            @click="toggle = false">X</button>
          <span>
            test
          </span> <span>
            test
          </span> <span>
            test
          </span> <span>
            test
          </span>
        </div>
      </div>
      <div class="lg:mx-10 md:m-auto hidden lg:block">
        <div class="flex flex-row items-center gap-x-24">
          <nuxt-link to="#"><i class="fab fa-pied-piper text-black fa-5x"></i>
          </nuxt-link>
          <div class="flex flex-row w-full gap-20">
            <nuxt-link class="font-bold" to="#">
              خانه
            </nuxt-link>
            <nuxt-link class="font-bold" to="/">
              <div class="flex gap-1 items-center dropdown">
                <span>دوره ها</span>
                <i class="fas fa-chevron-down text-black fa-sm"></i>
                <div class="dropdown-content">
                  <a class="hover:text-yellow-600 hover:font-bold text-gray-700 items-center flex gap-x-1 p-1"
                     href="#">
                    <span>سفیر</span>
                  </a>
                  <a class="hover:text-yellow-600 hover:font-bold text-gray-700 items-center flex gap-x-1 p-1"
                     href="#">
                    <span>ماینر</span>
                  </a>
                  <a class="hover:text-yellow-600 hover:font-bold text-gray-700 items-center flex gap-x-1 p-1"
                     href="#">
                    <span>شهروند</span>
                  </a>
                  <a class="hover:text-yellow-600 hover:font-bold text-gray-700 items-center flex gap-x-1 p-1"
                     href="#">
                    <span>شریک تجاری</span>
                  </a>
                </div>

              </div>
            </nuxt-link>
            <nuxt-link class="font-bold" to="#">
              وبلاگ
            </nuxt-link>
            <nuxt-link class="font-bold" to="#">
              تماس باما
            </nuxt-link>
            <nuxt-link class="font-bold" to="#">
              درباره ما
            </nuxt-link>
          </div>
          <nuxt-link to="#">
            <i class="far fa-user-circle text-black fa-2x"></i>
          </nuxt-link>
        </div>
      </div>
    </div>
    <div>
      <Nuxt class="lg:mt-24 mt-4"/>
    </div>
    <footer class="bg-yellow-500">
      <div class="container m-auto py-20">
        <div class="grid lg:grid-cols-4 grid-cols-1 gap-y-8 px-4 lg:px-2 gap-x-20">
          <div class="flex flex-col gap-y-4">
            <span class="text-black relative font-bold">
              درباره ما
              <div class="w-12 -bottom-2 bg-white h-0.5 rounded absolute"></div>
            </span>
            <p class="text-sm mt-4">قالب Glaxdu یک قالب مدرن و جدید طراحی شده بر پایه بوت استرپ 4 و کاملا واکنشگرا
              میباشد.</p>
            <div class="flex flex-row gap-x-2">
              <i class="fas fa-home text-black lg:fa-lg"></i>
              <span class="text-sm"> تهران، شرکت پژوهشگران جوان
                </span>
            </div>
            <div class="flex flex-row gap-x-2">
              <i class="fas fa-envelope lg:fa-lg"></i>
              <a class="text-sm" href="#">Avid@gamil.com</a>
            </div>
            <div class="flex flex-row gap-x-2">
              <i class="fas fa-phone text-black lg:fa-lg"></i>
              <span class="text-sm">98 558 547 589+</span>
            </div>
          </div>
          <div class="flex flex-col gap-y-4">
            <span class="text-black relative font-bold">
               دسترسی سریع
              <div class="w-12 -bottom-2 bg-white h-0.5 rounded absolute"></div>
            </span>
            <nuxt-link class="text-sm mt-4" to="#">
              خانه
            </nuxt-link>
            <nuxt-link class="text-sm" to="#">
              درباره ما
            </nuxt-link>
            <nuxt-link class="text-sm" to="#">
              دوره ها
            </nuxt-link>
            <nuxt-link class="text-sm" to="#">
              پذیرش
            </nuxt-link>
            <nuxt-link class="text-sm" to="#">
              شرایط و ضوابط
            </nuxt-link>

          </div>
          <div class="flex flex-col gap-y-4">
            <span class="text-black relative font-bold">
           دوره ها
            <div class="w-12 -bottom-2 bg-white h-0.5 rounded absolute"></div>
            </span>
            <nuxt-link class="text-sm mt-4" to="#">
              دوره تحصیلات تکمیلی
            </nuxt-link>
            <nuxt-link class="text-sm" to="#">
              دوره های کارشناسی ارشد
            </nuxt-link>
            <nuxt-link class="text-sm" to="#">
              دوره های دیپلم
            </nuxt-link>
            <nuxt-link class="text-sm" to="#">
              دوره های زیر دیپلم
            </nuxt-link>
            <nuxt-link class="text-sm" to="#">
              دیگر دوره ها
            </nuxt-link>
          </div>
          <div class="flex flex-col gap-y-4">
             <span class="text-black relative font-bold">
            شبکه های اجتماعی
            <div class="w-12 -bottom-2 bg-white h-0.5 rounded absolute"></div>
            </span>
            <div class="flex flex-col  gap-y-4 justify-center">
              <div class="flex flex-row gap-4">
                <i class="fab fa-whatsapp fa-lg"></i>
                <i class="fab fa-instagram fa-lg"></i>
                <i class="fab fa-telegram-plane fa-lg"></i>
              </div>
              <div class="flex flex-row gap-4">
                <i class="fab fa-linkedin-in fa-lg"></i>
                <i class="fab fa-twitter fa-lg"></i>
                <i class="fab fa-youtube fa-lg"></i>
              </div>
            </div>
          </div>
          <div></div>
        </div>
      </div>
      <div class="flex justify-center text-center text-sm border-t py-2 border-black">
        کپی رایت © GLAXDU . تمامی حقوق محفوظ است.
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  data() {
    return {
      is_desktop: null,
      toggle: false,
      user_name: null,
    }
  },
}
</script>

<style scoped>


</style>
