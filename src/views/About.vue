<template>
  <div class="about">
    <h1>This is an about page</h1>
    <currencies />
  </div>
</template>

<script>
// @ is an alias to /src

import Currencies from "../components/Currencies.vue";
export default {
  name: "About",
  components: {
    Currencies,
  },
};
</script>
