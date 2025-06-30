<template>
  <div class="overflow-x-hidden bg-dark-blue">
    <header>
      <div class="relative bottom-0 font-rubik text-base font-normal text-white">
        <div
          class="realtive mx-auto flex max-w-7xl items-center justify-between py-6 px-4 sm:px-6 md:space-x-10 lg:px-8"
        >
          <a href="/" class="flex text-base text-white font-bold">
            <span class="text-orange">Keywords &nbsp;</span>ROI Calculator
          </a>

          <div
            class="absolute bottom-0 left-0 h-[1px] w-screen bg-medium-blue sm:-translate-x-10"
          ></div>
        </div>
      </div>
    </header>

    <nuxt />

    <footer
      class="mt-24 flex w-full flex-col items-center justify-center space-y-16 bg-gradient-to-br from-[#222839] to-[#12151E] px-4 pt-20 pb-20 font-rubik text-grey sm:mt-32 sm:space-y-20"
    >
      <div class="flex w-full max-w-7xl flex-col items-center justify-center space-y-16">
        <div class="flex flex-col items-center justify-center space-y-4">

          <p class="text-sm">© rights reserved.</p>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  head() {
    return {
      title: 'Keywords ROI Calculator',
      meta: [
        {
          hid: 'description',
          name: 'description',
          content: 'Import Semrush Excel to Generate ROI Table. | Keywords ROI Calculator'
        }
      ]
    }
  }
}
</script>
