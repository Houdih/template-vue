<template>
  <ul class="nav justify-content-center">
    <li>
      <router-link class="item" to="/home">Home</router-link>
    </li>
    <li>
      <router-link class="item" to="/services">Services</router-link>
    </li>
    <li>
      <router-link class="item" to="/about">A propos</router-link>
    </li>
  </ul>
</template>

<script>
export default {
  name: "NavBase",
};
</script>

<style scoped lang="scss">
li {
  padding: 20px;
}
.item {
  color: black;
  &:hover {
    color: $color-primary;
    text-decoration: underline;
    text-underline-offset: 5px;
  }
}
</style>
