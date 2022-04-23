<template>
  <section>home</section>
</template>

<script lang="ts">
import { defineComponent, ref } from "vue";

export default defineComponent({
  name: "home-index",
  setup() {
    const count = ref(1);

    return {
      count,
    };
  },
});
</script>
