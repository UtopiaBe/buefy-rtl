<template>
  <div :dir="$dir()">
    <Header />
    <nuxt />
  </div>
</template>

<script>
export default {
  data() {
    return {
      rtl: true
    }
  }
}
</script>

<style lang="scss">
// Import Bulma's core
@import "~bulma/sass/utilities/_all";

$rtl: true;

// Import Bulma and Buefy styles
@import "~bulma";
@import "~buefy/src/scss/buefy";
</style>