<template>
  <div class="nav">
    <router-link to="/">xxx</router-link> |
    <router-link to="/labels">labels</router-link> |
    <router-link to="/statistics">statistics</router-link>
  </div>
</template>

<script lang="ts">
export default {
  name: 'Nav'
};
</script>

<style lang="scss" scoped>
.nav {
  border: 1px solid red;
}
</style>