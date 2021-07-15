<template>
  <Section title="Quem sou eu?" icon="far fa-user-graduate">
    <template v-slot:subtitle>"O que é ser?"</template>
    <p>
      Músico, amante de xadrez e de raciocínio lógico. Em contato com
      programação web desde 2017 e, desde então, apaixonado por tecnologia.
      Sempre em busca de conhecimento, novas experiências... E de um pão de
      queijo.
    </p>
    <PageLink href="#sobre">Um longo texto sobre mim... </PageLink>
  </Section>
</template>

<script setup>
import Section from "../tiny/Section.vue";
import PageLink from "../tiny/PageLink.vue";
</script>

<style>
article#whoami {
  width: 100%;
  display: block;
  position: absolute;
  top: 0;
  left: 0;
  background: white;
}
</style>