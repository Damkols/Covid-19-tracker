<template>
  <Header />
  <div class="container">
    <router-view />
  </div>
</template>

<script>
import Header from "@/components/Header";

export default {
  components: {
    Header,
  },
};
</script>

<style>
.container {
  width: min(90%, 1200px);
  margin-inline: auto;
}
</style>
