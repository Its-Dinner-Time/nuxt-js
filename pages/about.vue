<template>
  <div>
    <h1>{{ title }}</h1>
    <nuxt-link to="/">Home</nuxt-link>
  </div>
</template>

<script>
const title = "About";

export default {
  layout: "default2",
  data() {
    return {
      title,
    };
  },
};
</script>

<style lang="scss" scoped></style>
