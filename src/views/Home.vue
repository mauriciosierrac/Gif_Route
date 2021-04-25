<template>
  <div class="home">
    <div class="">
      <hello-world></hello-world>
      <div class="container mt-3 ml-3 mr-3 text-center">
        <img
          src="./logos/logovue.svg.png"
          alt="VueJs"
          class="img-fluid rounded"
        />

        <img
          src="./logos/logoboot.png"
          alt="VueJs"
          class="img-fluid rounded"
        />
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "Home",
  components: {
    HelloWorld,
  },
};
</script>

<style>
img {
  width: 30%;
}
</style>
