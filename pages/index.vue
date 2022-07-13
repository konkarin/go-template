<template>
  <div>
    <GoTemplate :label="label" />
  </div>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  name: "IndexPage",
  asyncData() {
    return {
      label: "{{ variant }}",
    };
  },
});
</script>
