    <template>
      <!-- Slider -->
      <div class="px-4 lg:px-8 py-10">
        <div data-hs-carousel='{
      "loadingClasses": "opacity-0"
    }' class="relative">
          <div
            class="hs-carousel mt-10 relative overflow-hidden w-full h-[30rem] md:h-[calc(100vh-106px)] bg-gray-100 rounded-2xl">
            <div
              class="hs-carousel-body absolute top-0 bottom-0 start-0 flex flex-nowrap transition-transform duration-700 opacity-0">
              <!-- Item -->
              <div class="hs-carousel-slide ">
                <div class="bg-black z-[1]">
                  <div
                    class="h-[30rem] md:h-[calc(100vh-106px)] flex flex-col relative bg-[url('~/assets/img/hero.jpg')] bg-cover bg-blend-multiply bg-center bg-no-repeat">
                    <!-- Overlay -->
                    <div class="absolute inset-0 bg-black opacity-40 z-[2]"></div>
                    <!-- Content -->
                    <div class="relative mt-auto w-screen md:max-w-lg ps-5 pb-5 md:ps-10 md:pb-10 z-[3]">
                      <span class="block text-white text-xl md:text-3xl opacity-100 font-bold">
                        SMK Pusat keunggulan<br>SMKN 4 Tasikmalaya
                      </span>
                      <div class="mt-5">
                        <button type="button"
                          class="py-3 px-4 inline-flex items-center gap-x-2 text-sm font-medium rounded-lg border border-transparent bg-blue-600 text-white hover:bg-blue-700 focus:outline-none focus:bg-blue-700 disabled:opacity-50 disabled:pointer-events-none"
                          aria-haspopup="dialog" aria-expanded="false" aria-controls="hs-bg-gray-on-hover-cards"
                          data-hs-overlay="#hs-bg-gray-on-hover-cards">
                          Tonton Video
                        </button>
                      </div>
                    </div>
                  </div>
                </div>
              </div>

              <!-- End Item -->

              <!-- Item -->
              <div class="hs-carousel-slide">
                <div
                  class="h-[30rem] md:h-[calc(100vh-106px)] flex flex-col bg-[url('https://images.unsplash.com/photo-1612287230202-1ff1d85d1bdf?q=80&w=1920&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D')] bg-cover bg-center bg-no-repeat">
                  <div class="mt-auto w-2/3 md:max-w-lg ps-5 pb-5 md:ps-10 md:pb-10">
                    <span class="block text-white">CoolApps</span>
                    <span class="block text-white text-xl md:text-3xl">From mobile apps to gaming consoles</span>
                    <div class="mt-5">
                      <a class="py-2 px-3 inline-flex items-center gap-x-2 text-sm font-medium rounded-xl bg-white border border-transparent text-black hover:bg-gray-100 focus:outline-none focus:bg-gray-100 disabled:opacity-50 disabled:pointer-events-none"
                        href="#">
                        Read Case Studies
                      </a>
                    </div>
                  </div>
                </div>
              </div>
              <!-- End Item -->

              <!-- Item -->
              <div class="hs-carousel-slide">
                <div
                  class="h-[30rem] md:h-[calc(100vh-106px)] flex flex-col bg-[url('https://images.unsplash.com/photo-1629666451094-8908989cae90?q=80&w=1920&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D')] bg-cover bg-center bg-no-repeat">
                  <div class="mt-auto w-2/3 md:max-w-lg ps-5 pb-5 md:ps-10 md:pb-10">
                    <span class="block text-white">Grumpy</span>
                    <span class="block text-white text-xl md:text-3xl">Bringing Art to everything</span>
                    <div class="mt-5">
                      <a class="py-2 px-3 inline-flex items-center gap-x-2 text-sm font-medium rounded-xl bg-white border border-transparent text-black hover:bg-gray-100 focus:outline-none focus:bg-gray-100 disabled:opacity-50 disabled:pointer-events-none"
                        href="#">
                        Read Case Studies
                      </a>
                    </div>
                  </div>
                </div>
              </div>
              <!-- End Item -->
            </div>
          </div>

          <!-- Arrows -->
          <button type="button"
            class="hs-carousel-prev hs-carousel-disabled:opacity-50 disabled:pointer-events-none absolute inset-y-0 start-0 inline-flex justify-center items-center w-12 h-full text-white hover:bg-white/20 rounded-s-2xl focus:outline-none focus:bg-white/20">
            <span class="text-2xl" aria-hidden="true">
              <svg class="shrink-0 size-3.5 md:size-4" xmlns="http://www.w3.org/2000/svg" width="16" height="16"
                fill="currentColor" viewBox="0 0 16 16">
                <path fill-rule="evenodd"
                  d="M11.354 1.646a.5.5 0 0 1 0 .708L5.707 8l5.647 5.646a.5.5 0 0 1-.708.708l-6-6a.5.5 0 0 1 0-.708l6-6a.5.5 0 0 1 .708 0z">
                </path>
              </svg>
            </span>
            <span class="sr-only">Previous</span>
          </button>

          <button type="button"
            class="hs-carousel-next hs-carousel-disabled:opacity-50 disabled:pointer-events-none absolute inset-y-0 end-0 inline-flex justify-center items-center w-12 h-full text-white hover:bg-white/20 rounded-e-2xl focus:outline-none focus:bg-white/20">
            <span class="sr-only">Next</span>
            <span class="text-2xl" aria-hidden="true">
              <svg class="shrink-0 size-3.5 md:size-4" xmlns="http://www.w3.org/2000/svg" width="16" height="16"
                fill="currentColor" viewBox="0 0 16 16">
                <path fill-rule="evenodd"
                  d="M4.646 1.646a.5.5 0 0 1 .708 0l6 6a.5.5 0 0 1 0 .708l-6 6a.5.5 0 0 1-.708-.708L10.293 8 4.646 2.354a.5.5 0 0 1 0-.708z">
                </path>
              </svg>
            </span>
          </button>
          <!-- End Arrows -->
        </div>
      </div>
      <!-- End Slider -->

      <!-- Popup -->
      <div id="hs-bg-gray-on-hover-cards"
        class="hs-overlay hidden size-full fixed top-0 start-0 z-[80] overflow-x-hidden overflow-y-auto pointer-events-none"
        role="dialog" tabindex="-1" aria-labelledby="hs-bg-gray-on-hover-cards-label">
        <div
          class="hs-overlay-open:mt-7 hs-overlay-open:opacity-100 hs-overlay-open:duration-500 mt-0 opacity-0 ease-out transition-all sm:max-w-4xl sm:w-full m-3 h-[calc(100%-3.5rem)] sm:mx-auto">
          <div
            class="max-h-full overflow-hidden flex flex-col bg-white border shadow-sm rounded-xl pointer-events-auto">
            <div class="flex justify-center items-center py-3 px-4 border-b">
              <iframe width="1280" height="485" src="https://www.youtube.com/embed/iBtaSZEneMQ?si=GBiisWMAZYCae9Ks"
                title="YouTube video player" frameborder="0"
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
                referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
            </div>
          </div>
        </div>
      </div>
    </template>
