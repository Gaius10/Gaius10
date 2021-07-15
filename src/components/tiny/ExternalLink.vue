<template>
  <a class="externalLink" target="_blank" :href="href">
    <slot /><i class="fas fa-external-link-alt"></i>
  </a>
</template>

<script>
export default {
  props: {
    href: String,
  },
};
</script>

<style>
a.externalLink {
  color: blue;
  cursor: pointer;
}
a.externalLink:hover {
  text-decoration: underline;
}

a.externalLink > i {
  display: inline;
  margin-left: 0.2rem;
}
</style>