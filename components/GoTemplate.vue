<template>
  <div>
    {{ label }}
  </div>
</template>

<script>
export default {
  name: "GoTemplate",
  props: {
    label: {
      type: String,
      required: true,
    },
  },
};
</script>

<style>
.nuxt-logo {
  height: 180px;
}
</style>
