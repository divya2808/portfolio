<template>
  <div class="bg-black flex items-center justify-center">
    <div class="flex justify-center flex-col">
      <div class="text-white text-3xl text-center">Hello!</div>
      <div class="my-4 text-center">
        <p class="text-white text-lg">My name is Divya Kandlakunta. I'm a full stack web developer.</p>
        <p class="text-white text-lg">Building creative and elegant websites, solving problems and providing innovative and efficient solutions is my passion</p>
        <p class="text-white text-lg">If you are seeking web presense or an employer looking to hire please reach out to me</p>
        <button class="px-8 py-3 bg-blue-400 text-black my-6 hover:bg-white hover:text-blue-600 transition-all font-semibold">
          <nuxt-link to="/contact" class="uppercase outline-none">Contact me</nuxt-link>
        </button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'About'
}
</script>

<style lang="scss" scoped>

</style>
