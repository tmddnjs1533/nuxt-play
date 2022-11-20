<template>
  <div>
    <header class="bg-gray-800 h-16 px-6 flex">
      <nuxt-link to="/" class="text-white h-full flex items-center mr-9">
        <font-awesome-icon icon="fa-solid fa-play" />
        PLAY
      </nuxt-link>
      <nuxt-link
        to="/blog"
        class="px-4 h-full flex items-center text-gray-300 hover:bg-gray-700 hover:text-white"
      >
        Blog
      </nuxt-link>
      <div class="flex-1"></div>
      <div class="flex items-center">
        <label
          for="default-toggle"
          class="inline-flex relative items-center cursor-pointer"
        >
          <input
            id="default-toggle"
            type="checkbox"
            value=""
            class="sr-only peer"
          />
          <span
            class="w-11 h-6 bg-gray-200 peer-focus:outline-none peer-focus:ring-4 peer-focus:ring-blue-300 dark:peer-focus:ring-blue-800 rounded-full peer dark:bg-gray-700 peer-checked:after:translate-x-full peer-checked:after:border-white after:content-[''] after:absolute after:top-[2px] after:left-[2px] after:bg-white after:border-gray-300 after:border after:rounded-full after:h-5 after:w-5 after:transition-all dark:border-gray-600 peer-checked:bg-blue-600"
          ></span>
        </label>
      </div>
    </header>
    <div class="container">
      <Nuxt />
    </div>
  </div>
</template>

<script>
export default {
  name: 'Default',
}
</script>

<style scoped></style>
