<template>
  <main class="Page Page--isTour Page--isTourHome py-20 flex-grow">

    <div class="Tour Tour--GenderSelection text-center">

      <section class="TourStep GenderSelection" data-step="" data-answers="">

        <h3 class="TourStep__subtitle TourStep__subtitle--smaller text-2xl font-black mb-4">
          Get your personalized
        </h3>

        <h1 class="TourStep__title TourStep__title--colored text-green-400 text-5xl font-black mb-4">
          KETO DIET PLAN
        </h1>

        <h2 class="TourStep__subtitle TourStep__subtitle--smaller text-2xl font-black mb-4">
          All natural, healthy plans to lose weight
        </h2>

        <p class="text-xl mb-4">Take the free quiz below</p>

        <img
          src="https://cdn.ketobody.life/themes/default/arrow_down.svg"
          srcset="https://cdn.ketobody.life/themes/default/arrow_down.svg"
          alt="arrow down"
          class="w-6 mx-auto my-5"
        >

        <div class="GenderSelection__buttons w-56 mx-auto mb-5">

          <button class="Button bg-pink-500 rounded-full flex justify-center items-center text-white mb-4 w-full px-5">
            <span class="flex-1">WOMAN</span>
            <img
              src="https://cdn.ketobody.life/themes/default/female.svg"
              srcset="https://cdn.ketobody.life/themes/default/female.svg"
              alt="female"
              class="flex-shrink-0"
            >
          </button>

          <button class="Button bg-blue-500 rounded-full flex justify-center items-center text-white w-full px-5">
            <span class="flex-1">MAN</span>
            <div class="Button__icon">
              <img
                src="https://cdn.ketobody.life/themes/default/male.svg"
                srcset="https://cdn.ketobody.life/themes/default/male.svg"
                alt="female"
                class="flex-shrink-0"
              >
            </div>
          </button>

        </div>

      </section>
    </div>
    <slot></slot>
  </main>
</template>

<script>
export default {
  name: "Main"
}
</script>

<style scoped>

</style>
