<template>
  <div id="root">
    <p>{{originalPrice}}</p>
    <p>{{doublePrice}}</p>
    <p>{{tripplePrice}}</p>
  </div>
</template>

<script>
import { mapGetters } from "vuex";

export default {
  computed: {
    ...mapGetters(["originalPrice", "doublePrice", "triplePrice"])
  }
};
</script>

<style>
</style>