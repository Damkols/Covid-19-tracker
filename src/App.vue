<template>
  <Header />
  <div class="contain">
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
.contain {
  width: min(90%, 1200px);
  margin-inline: auto;
}
</style>
