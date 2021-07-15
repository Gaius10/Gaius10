<template>
  <a :href="href" class="pageLink">
    <i class="fas fa-chevron-left" v-if="type == 'back'"></i>

    <slot />

    <i class="fas fa-chevron-right" v-if="type != 'back'"></i>
  </a>
</template>

<script>
export default {
  props: {
    type: String,
    href: String,
  },
};
</script>

<style>
a.pageLink {
  display: block;
  text-align: center;
  padding: 1rem 0;
  margin: 1rem 0;

  cursor: pointer;

  font-size: 1.1rem;
  color: #555;

  border-radius: 1rem;
  background-color: var(--colorDocumentSecondary);
}

a.pageLink:hover {
  background: #ccc;
  color: black;
}

a.pageLink > i.fas.fa-chevron-right,
a.pageLink > i.fas.fa-chevron-left {
  font-size: 0.8rem;
  margin: 0 0.7rem;
  vertical-align: middle;
}

@media only screen and (min-width: 1200px) {
  a.pageLink {
    transition-duration: 0.4s;
  }
}
</style>
