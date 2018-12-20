<template>
  <div class="container">
    <h1>Vuex Section</h1>
    <hr />
    <app-result />
    <hr />
    <app-other />
    <br />
    <app-counter />
  </div>
</template>

<script>
import AppCounter from "./components/Counter";
import AppResult from "./components/Result";
import AppOther from "./components/Other";
export default {
  components: {
    AppResult,
    AppCounter,
    AppOther
  }
};
</script>

<style></style>
