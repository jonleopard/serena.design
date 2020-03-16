<template>
  <div class="container mx-auto">
    <div class="flex h-screen">
      <div class="m-auto md:flex lg:flex">
        <logo />
        <div class="flex-col m-auto">
          <div class="text-center md:text-left">
            <div class="flex">
              <h1 class="font-serif text-5xl text-gray-700 lg:text-6xl">
                serena
              </h1>
              <h1 class="font-serif text-5xl text-pink-600 lg:text-6xl">
                .design
              </h1>
            </div>
            <h2 class="font-serif text-2xl text-gray-600">coming soon</h2>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
  @apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
</style>
