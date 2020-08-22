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
      <div class="text-sm lg:flex-grow navbar-links">
        <nuxt-link
          to="/projects"
          class="projects text-xl block px-5 py-2 rounded lg:inline-block lg:mt-0 text-gray-800 hover:text-black"
        >Projects</nuxt-link>
        <nuxt-link
          to="/blogs"
          class="blogs text-xl block lg:inline-block px-5 py-2 rounded lg:mt-0 text-gray-800 hover:text-black"
        >Blogs</nuxt-link>
        <nuxt-link
          to="/design"
          class="design text-xl block lg:inline-block px-5 py-2 rounded lg:mt-0 text-gray-800 hover:text-black"
        >Design</nuxt-link>
        <nuxt-link
          to="/about"
          class="about text-xl block lg:inline-block px-5 py-2 rounded lg:mt-0 text-gray-800 hover:text-black"
        >About Me</nuxt-link>
      </div>
    </div>
  </nav>
</template>

<script>
export default {};
</script>

<style lang="scss">
.navbar-links .active-link {
    transition: all 200ms ease-in;
  &.projects {
    background-color: #0052cc;
    color: white;
  }
  &.design {
    background-color: #172b4d;
    color: white;
  }
  &.about {
    background-color: #FF5630;
    color: white;
  }
  &.blogs {
    background-color: #6554C0;
    color: white;
  }
}
</style>