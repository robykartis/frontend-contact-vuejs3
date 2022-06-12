<template>
  <TemplateHeader title="ABNATION" />
  <router-view></router-view>
</template>

<script>
import TemplateHeader from "./components/TemplateHeader.vue";
export default {
  name: "App",
  components: {
    TemplateHeader,
  },
};
</script>

<style>
</style>
