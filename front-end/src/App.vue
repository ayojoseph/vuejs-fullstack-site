<template>
  <NavBar />
  <!-- <h1>Olive Garden</h1> -->

  <div class="page-wrap">
    <router-view></router-view>
  </div>
</template>

<script>
import NavBar from "@/components/NavBar.vue";
export default {
  name: "App",
  components: {
    NavBar,
  },
};
</script>
