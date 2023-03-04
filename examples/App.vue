<template>
  <div id="app">
    <WxSelect />
  </div>
</template>

<script>
import WxSelect from "../packages/select/src/Select.vue";

export default {
  name: "App",
  components: { WxSelect: WxSelect },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
