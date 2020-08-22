<template>
  <nav class="flex items-center justify-between flex-wrap py-10 max-w-screen-xl mx-auto my-0">
    <div class="flex items-center flex-shrink-0 mr-6">
      <nuxt-link to="/" class="font-semibold text-3xl tracking-tight">Aayush Joglekar</nuxt-link>
    </div>
    <div class="block lg:hidden">
      <button
        class="flex items-center px-3 py-2 border rounded text-teal-200 border-teal-400 hover:text-white hover:border-white"
      >
        <svg class="fill-current h-3 w-3" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
          <title>Menu</title>
          <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z" />
        </svg>
      </button>
    </div>
    <div class="lg:flex lg:items-center lg:w-auto">
      <div class="text-sm lg:flex-grow">
        <nuxt-link
          to="/projects"
          class="text-xl block mt-4 lg:inline-block lg:mt-0 text-gray-800 hover:text-black mr-4"
        >Projects</nuxt-link>
        <nuxt-link
          to="/blogs"
          class="text-xl block mt-4 lg:inline-block lg:mt-0 text-gray-800 hover:text-black mr-4"
        >Blogs</nuxt-link>
        <nuxt-link
          to="/design"
          class="text-xl block mt-4 lg:inline-block lg:mt-0 text-gray-800 hover:text-black mr-4"
        >Design</nuxt-link>
        <nuxt-link
          to="/about"
          class="text-xl block mt-4 lg:inline-block lg:mt-0 text-gray-800 hover:text-black mr-4"
        >About Me</nuxt-link>
      </div>
      <div>
        <a
          href="#"
          class="inline-block text-sm px-4 py-2 leading-none border rounded text-white border-white hover:border-transparent hover:text-teal-500 hover:bg-white mt-4 lg:mt-0"
        >Download</a>
      </div>
    </div>
  </nav>
</template>

<script>
export default {};
</script>

<style lang="scss">
</style>