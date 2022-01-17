<template>
  <div>
    <div class="w-full">
      <main>
        <section class="relative overflow-hidden">
          <div class="  relative z-0">
            <div v-swiper:mySwiper="swiperOption">
              <div class="swiper-wrapper ">
                <div v-for="banner in banners" :key="banner" class="swiper-slide">
                  <img :src="banner" class="slider-img">
                </div>
              </div>
              <div class="swiper-pagination bg-black"></div>
            </div>
          </div>
        </section>
      </main>
      <div class="relative">
        <div class="-m-24 lg:mx-10 mx-4 grid lg:grid-cols-4 grid-flow-row">
          <div class="bg-stone-600">
            <div class="flex flex-row gap-3 p-10 text-sm text-white">
              <i class="fab fa-discourse fa-2x"></i>
              <div>
                <h2 class="font-bold">پشتیبانی آنلاین</h2>
                <p>لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان گرافیک است.</p>
              </div>
            </div>
          </div>
          <div class="bg-stone-700">
            <div class="flex flex-row gap-3 p-10 text-base text-white">
              <i class="fab fa-discourse fa-2x"></i>
              <div>
                <h2 class="font-bold">پشتیبانی آنلاین</h2>
                <p>لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان گرافیک است.</p>
              </div>
            </div>
          </div>
          <div class="bg-stone-800">
            <div class="flex flex-row gap-3 p-10 text-sm text-white">
              <i class="fab fa-discourse fa-2x"></i>
              <div>
                <h2 class="font-bold">پشتیبانی آنلاین</h2>
                <p>لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان گرافیک است.</p>
              </div>
            </div>
          </div>
          <div class="bg-stone-900">
            <div class="flex flex-row gap-3 p-10 text-sm text-white">
              <i class="fab fa-discourse fa-2x"></i>
              <div>
                <h2 class="font-bold">پشتیبانی آنلاین</h2>
                <p>لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان گرافیک است.</p>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="container m-auto">
        <div class="mt-32 px-4 pt-10 container m-auto">
          <div class="flex lg:flex-row my-4 flex-col gap-4">
            <div class="flex flex-col gap-y-4">
              <div>
                <h1 class="inline-block px-2 font-bold text-4xl py-0.5 -skew-y-3 btn">
                  <span class="text-white relative z-30 text-stone-900"> درباره </span>
                  <span class="relative text-white z-30">ما</span>
                </h1>
              </div>
              <p class="content-abuotus">
                قالب Glaxdu یک قالب مدرن و جدید بر پایه بوت استرپ 4 میباشد. Glaxdu برای وب سایت های آموزشی،برگزاری
                رویداد و دوره های آموزشی و تجارت الکترونیکی است. شما می توانید از این قالب HTML برای دانشگاه ، دبیرستان
                ، مهد کودک ، مرکز مربیگری ، مشاوره تحصیلات و غیره استفاده کنید.
              </p>
              <div>
                <button class="btn rounded-full px-10 py-3"> درباره ما</button>
              </div>
            </div>
            <video autoplay controls height="500" width="500">
              <source src="https://cdn.bitdegree.org/learn/Pexels%20Videos%203373.mp4?raw=true" type="video/mp4">
              Video tag is unsupported in this browser
            </video>
          </div>
        </div>
      </div>
      <div class="bg-amber-50">
        <div class="container m-auto">
          <div class="my-10 px-4 py-8 container m-auto">
            <div class="flex lg:flex-row my-4 flex-col gap-4">
              <div class="flex flex-col gap-y-4">
                <div>
                  <h1 class="inline-block px-2 font-bold text-4xl py-0.5 -skew-y-3 btn">
                    <span class="text-white relative z-30 text-stone-900"> اخبار </span>
                    <span class="relative text-white z-30">آوید</span>
                  </h1>
                </div>
                <p class="content-abuotus">
                  قالب Glaxdu یک قالب مدرن و جدید بر پایه بوت استرپ 4 میباشد. Glaxdu برای وب سایت های آموزشی،برگزاری
                  <br/>
                  رویداد و دوره های آموزشی و تجارت الکترونیکی است
                </p>
              </div>
            </div>
            <div>
              <div class="flex flex-col lg:grid grid-cols-4">
                <nuxt-link to="#">
                  <div class="flex flex-col gap-4 overflow-hidden relative bg-white  group rounded-lg">
                    <img
                      class="transform transition duration-500 group-hover:opacity-50  group-hover:scale-110 relative"
                      src="~assets/img/event-1.jpg">
                    <div class="p-4">
                      <span class="font-bold"> کنفرانس</span>
                      <p class="p-2 text-sm text-ellipsis">
                        لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان گرافیک است.
                        لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ
                      </p>
                    </div>

                  </div>
                </nuxt-link>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="container m-auto">
        <div class="px-4 py-8 container m-auto">
          <div class="flex my-4 flex-col gap-4">
            <div class="flex flex-col gap-y-4">
              <div>
                <h1 class="inline-block px-2 font-bold text-4xl py-0.5 -skew-y-3 btn">
                  <span class="text-white relative z-30 text-stone-900"> دوره های </span>
                  <span class="relative text-white z-30">ما</span>
                </h1>
              </div>
              <p class="content-abuotus">
                لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان گرافیک است.
                <br/>
                لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ </p>
              <div>
                <div class="container my-10 m-auto">
                  <div class="flex flex-col gap-4 lg:grid lg:grid-cols-4">
                    <nuxt-link
                      class=" transition duration-300 ease-in-out xl:mb-0 lg:mb-0 md:mb-0 mb-6 cursor-pointer group"
                      to="#">
                      <div
                        class="flex bg-white rounded-lg overflow-hidden shadow group-hover:bg-opacity-25 flex-col relative">
                        <img class="transform transition duration-500 hover:scale-110 " src="~assets/img/course-3.jpg">
                        <div class="p-4 fd-cl group-hover:opacity-25">
                          <span class="font-bold">کارگاه ساخت و تجربه</span>
                          <p class="text-sm">لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از
                            طراحان گرافیک
                            است. </p>
                        </div>
                        <div
                          class="absolute flex flex-col justify-center transform transition duration-500 hover:scale-110  opacity-0 w-full fd-sh h-full group-hover:opacity-75 transform transition duration-500 hover:bg-amber-300">
                          <span class="absolute inset-x-0 left-0 bg-stone-900 text-white text-xs text-center py-1"> پذیرش ادامه دارد</span>
                          <span
                            class="text-xl font-bold text-black group-hover:bg-opacity-100 leading-relaxed text-center"> مدرس: استاد رفیعی </span>
                          <div class="pt-8 text-center">
                            <button
                              class="text-center rounded-lg p-2 bg-white group-hover:opacity-100 mt-3 text-black font-bold text-sm">
                              مشاهده بیشتر..
                            </button>
                          </div>
                        </div>
                      </div>
                    </nuxt-link>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="bg-amber-50 mt-10 py-8">
        <div class="container m-auto">
          <div class="px-4 py-8 container m-auto">
            <div class="flex my-4 flex-col gap-4">
              <div class="flex flex-col gap-y-4">
                <div>
                  <h1 class="inline-block px-2 font-bold text-4xl py-0.5 -skew-y-3 btn">
                    <span class="text-white relative z-30 text-stone-900"> اساتید </span>
                    <span class="relative text-white z-30">آوید</span>
                  </h1>
                </div>
                <p class="content-abuotus">
                  لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان گرافیک است.
                  <br/>
                  لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ </p>
                <div>
                  <div class="container my-10 m-auto">
                    <div class="flex flex-col gap-4 lg:grid lg:grid-cols-4">
                      <nuxt-link
                        class=" transition duration-300 ease-in-out xl:mb-0 lg:mb-0 md:mb-0 mb-6 cursor-pointer group"
                        to="#">
                        <div
                          class="flex bg-white overflow-hidden shadow group-hover:bg-opacity-25 flex-col relative">
                          <img class="transform transition duration-75 hover:scale-110 "
                               src="~assets/img/testi-b2.jpg">
                          <span
                            class="font-bold absolute p-4 left-0 bottom-0 bg-white text-black">محمد رفیعی</span>
                          <div
                            class="absolute flex flex-col justify-center items-center transform transition duration-75 hover:scale-110  opacity-0 w-full fd-sh h-full group-hover:opacity-90 transform transition duration-500 hover:bg-stone-600">
                            <div class="border h-full  m-7 p-1">
                              <span
                                class="text-xl  font-bold text-black group-hover:bg-opacity-100 leading-relaxed text-center"> مدرس: استاد رفیعی </span>
                              <span
                                class="text-lg  font-bold text-black group-hover:bg-opacity-100 leading-relaxed text-center"> کارشناسی ارشد </span>
                            </div>

                          </div>
                        </div>
                      </nuxt-link>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

    </div>
  </div>
</template>

<script>

export default {
  data() {
    return {
      banners: ['/slider.jpg', '/online-education.jpg',],
      swiperOption: {
        pagination: {
          el: '.swiper-pagination'
        },
      }
    }
  },
  mounted() {
    console.log('Current Swiper instance object', this.mySwiper)
    this.mySwiper.slideTo(3, 1000, false)
  }
}
</script>
<style scoped>
@media (min-width: 760px) {
  .slider-img {
    height: 90vh;
    background-repeat: no-repeat;
    background-size: cover;
    width: 100%;
  }
}

@media (max-width: 760px) {
  .slider-img {
    height: 87vh;
    background-repeat: no-repeat;
    background-size: cover;
    width: 100%;
  }
}

.content-abuotus {
  text-shadow: -2px -2px 11px rgba(171, 150, 150, 1);
}

.btn {
  background: linear-gradient(211.17deg, #EDD184 16.39%, #E8BD71 79.06%);
}

.content-div:hover .fd-cl {
  opacity: 0.25;
}

.content-div:hover .fd-sh {
  opacity: 1;
}

</style>

