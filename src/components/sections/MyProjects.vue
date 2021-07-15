<template>
  <Section title="Meus projetos" icon="far fa-user-graduate">
    <template v-slot:subtitle>
      "[...] Agora pegue sua melhor rima, supere-a, repita mil vezes [...]" -
      Eminem
    </template>
    <p>
      Essa parte aqui ainda está em construção, sou apenas um jovem
      recém-chegado ao lago negro da força... Mas você pode acompanhar meu
      desenvolvimento lá no
      <ExternalLink href="https://github.com/Gaius10">Github.</ExternalLink>
    </p>

    <template v-slot:footer>
      <span>"May the fork be with you."</span>
    </template>
  </Section>
</template>

<script setup>
import Section from "../tiny/Section.vue";
import ExternalLink from "../tiny/ExternalLink.vue";
</script>

<style>
</style>