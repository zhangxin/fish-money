<template>
  <div class="nav-wrapper">
    <div class="content">
      <slot></slot>
    </div>
    <Nav></Nav>
  </div>
</template>

<script lang="ts">
export default {
  name: 'Layout'
};
</script>

<style lang="scss" scoped>
.nav-wrapper {
  display: flex;
  flex-direction: column;
  height: 100vh;

  .content {
    flex-grow: 1;
    border: 1px solid blue;
    overflow: auto;
  }
}
</style>