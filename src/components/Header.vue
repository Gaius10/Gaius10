<template>
  <header class="mainHeader">
    <div>
      <div class="title">
        <h1>Caio Corrêa Chaves</h1>
        <p>
          Analista de Processamento de Dados na
          <a target="_blank" href="https://www.turimsoft.com.br/site/">
            Turim <i class="fas fa-external-link-alt"></i>
          </a>
        </p>
      </div>

      <SocialLinks />
    </div>
    <figure>
      <img src="../assets/caio.jpeg" alt="Caio Corrêa Chaves" />
      <figcaption>
        <i class="fas fa-envelope"></i> ccaioc.correa@gmail.com
      </figcaption>
    </figure>
  </header>
</template>

<script setup>
import SocialLinks from "./tiny/SocialLinks.vue";
</script>

<style>
header.mainHeader {
  width: 100%;
  padding: 2rem 1rem;
  color: white;
  text-align: center;
  background-color: var(--colorSecondary);
}

header.mainHeader .title h1 {
  font-size: 2rem;
  margin-bottom: 1rem;
}

header.mainHeader .title p {
  font-size: 1.3rem;
  line-height: 1.5rem;
  margin-bottom: 1.5rem;
  font-style: italic;
}

header.mainHeader .title p a {
  text-decoration: underline;
}

header.mainHeader figure {
  display: none;
}

@media only screen and (min-width: 1200px) {
  header.mainHeader .title {
    text-align: left;
  }
  header.mainHeader .title p a:hover {
    cursor: pointer;
  }

  header.mainHeader {
    display: flex;
    flex-direction: row;
    justify-content: space-around;
  }

  header.mainHeader > div:first-child {
    display: flex;
    flex-direction: column;
    justify-content: center;
    gap: 1rem;
  }
  header.mainHeader figure {
    display: block;
  }

  header.mainHeader figure img {
    width: 300px;
    height: 300px;
    border-radius: 50%;
  }
}
</style>