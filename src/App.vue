<template>
  <div class="">
    <div class="gg">
      <div class="max-w-lg"><Goten /></div>
    </div>
  </div>
</template>

<script>
import Goten from "./components/Goten.vue";

export default {
  name: "App",
  components: {
    Goten,
  },
};
</script>

<style>
.gg {
  display: flex;
  justify-content: center;
  justify-items: center;
}
</style>
