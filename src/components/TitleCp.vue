<template>
  <header class="header-wrapper">
    <h1 class="logo">
      <img src="@/assets/img/logo.png" alt="logo" class="logo">
      {{ title }}
    </h1>
  </header>
</template>

<script>
export default {
  name: 'TitleCp',
  props: ['title'],
};
</script>

<style lang="scss" scoped>
.header-wrapper {
  padding: $gutter-width;
  background-color: $secondary-color;
  color: $primary-color;
  font-size: 1.5em;
  .logo {
    width: 1.5em;
  }
}
</style>
