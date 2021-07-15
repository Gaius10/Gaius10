<template>
  <Section title="O cientista dentro de mim" icon="far fa-user-graduate">
    <template v-slot:subtitle>
      "Em algum lugar, alguma coisa incrível está esperando para ser
      descoberta." - Carl Sagan
    </template>

    <a
      class="scienceLink"
      target="_blank"
      href="https://www.divinopolis.cefetmg.br/"
      title="Centro Federal de Ensino Tecnológico de Minas Gerais"
    >
      <h4>
        Bacharel em Engenharia Mecatrônica
        <i class="fas fa-external-link-alt"></i>
      </h4>
      <h5>CEFET-MG (2019 - em curso)</h5>
    </a>

    <a
      class="scienceLink"
      target="_blank"
      href="https://www.divinopolis.cefetmg.br/"
      title="Etec Doutor Celso Giglio"
    >
      <h4>
        Técnico em Informática
        <i class="fas fa-external-link-alt"></i>
      </h4>
      <h5>Etec (2016 - 2018)</h5>
    </a>
  </Section>
</template>

<script setup>
import Section from "../tiny/Section.vue";
</script>

<style>
a.scienceLink {
  display: block;
  border-radius: 1rem;
  text-align: center;
  background-color: var(--colorDocumentSecondary);
  color: #333;
  padding: 1rem 0;
  cursor: pointer;
  transition-duration: 0.4s;
  margin-bottom: 1rem;
}
a.scienceLink:hover {
  background-color: #ccc;
  color: black;
}
</style>