<template>
  <div class="app">
    <uNav/>
    <router-view/>
  </div>
</template>

<script>
import uNav from "@/components/uNav";
export default {
  name: "App",
  components: {
    uNav,
  },
};
</script>

<style lang="scss">
#app {

}
</style>