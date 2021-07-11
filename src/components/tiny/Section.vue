<template>
  <section>
    <header>
      <h2>{{ title }}</h2>
      <h3>{{ subtitle }}</h3>
    </header>
  </section>
</template>

<script>
export default {
  props: {
    title: String,
    subtitle: String,
  },
};
</script>

<style>
</style>