<template>
  <div class="container min-h-screen">
    <div>I enjoy building side projects.</div>
    <div class="grid grid-cols-3 gap-4 mt-10">
      <div class="p-2" v-for="project in projects" :key="project.name">
          <img src="~/assets/projects/sample.png" />
        <h4>{{project.name}}</h4>
        <p class="text-gray-700">{{project.description}}</p>
        <p class="text-xs">{{project.year}}</p>
        <div>
            <span class="text-sm mr-2" v-for="tag in project.tech" :key="tag">{{ tag }}</span>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      projects: [
        {
          name: "Bunkr",
          description: "Study Resource Aggregation Platform",
          year: 2020,
          tech: ["Go", "VueJS", "MongoDB"],
        },
        {
          name: "Bunkr",
          description: "Study Resource Aggregation Platform",
          year: 2020,
          tech: ["Go", "VueJS", "MongoDB"],
        },
        {
          name: "Bunkr",
          description: "Study Resource Aggregation Platform",
          year: 2020,
          tech: ["Go", "VueJS", "MongoDB"],
        },
        {
          name: "Bunkr",
          description: "Study Resource Aggregation Platform",
          year: 2020,
          tech: ["Go", "VueJS", "MongoDB"],
        },
        {
          name: "Bunkr",
          description: "Study Resource Aggregation Platform",
          year: 2020,
          tech: ["Go", "VueJS", "MongoDB"],
        },
      ],
    };
  },
};
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
@apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
</style>
