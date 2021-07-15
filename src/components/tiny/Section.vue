<template>
  <section class="defaultSection">
    <header>
      <h2><i :class="icon"></i> {{ title }}</h2>
      <h3><slot name="subtitle" /></h3>
    </header>
    <slot />
    <p class="footer">
      <slot name="footer" />
    </p>
  </section>
</template>

<script>
export default {
  props: {
    title: String,
    icon: String,
  },
};
</script>

<style>
section.defaultSection {
  display: block;
  padding: 1rem;
  text-align: justify;
  font-size: 1.2rem;
  max-width: 900px;
  margin: 3rem auto;
}

section.defaultSection > header {
  border-left: 4px var(--colorMain) solid;
  padding: 0.2rem 1rem;
  margin-bottom: 1rem;
}

section.defaultSection > header h2 {
  font-size: x-large;
  font-weight: 700;
  color: #333;
  margin-bottom: 0.5rem;
}

section.defaultSection > header h3 {
  font-style: italic;
  color: var(--colorMain);
  line-height: 1.8rem;
}

section.defaultSection p {
  text-indent: 1.5rem;
  line-height: 1.9rem;
  margin: 1.5rem 0;
}

section.defaultSection > ul {
  margin: 1.5rem 0;
  list-style: inside;
  font-size: 1.05rem;
  font-style: italic;
}

section.defaultSection > .footer {
  display: flex;
  flex-direction: column;
  align-items: flex-end;
  font-style: italic;
  line-height: 1.7rem;
}
</style>