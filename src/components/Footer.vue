<template>
  <footer>
    <header>
      <h2>
        <i class="far fa-comments"></i>
        Quer conversar comigo?
      </h2>
    </header>

    <div class="socialFooterWrapper">
      <SocialLinks />
    </div>

    <div class="footerfooter">
      <span>Desenvolvido por: eu mesmo :)</span>
    </div>
  </footer>
</template>

<script setup>
import SocialLinks from "./tiny/SocialLinks.vue";
</script>

<style>
footer {
  display: block;
  position: relative;
  text-align: center;
  padding: 1rem 2rem;
  padding-bottom: 4rem;
  background-color: var(--colorSecondary);
  color: white;
}

footer header {
  margin: 2rem 0;
  font-size: 1.5rem;
}

footer div.socialFooterWrapper {
  max-width: 500px;
  margin: 1rem auto;
}

footer .footerfooter {
  position: absolute;
  bottom: 0;
  left: 0;

  width: 100%;
  text-align: center;
  /* background-color: #3b4358; */
  background-color: var(--colorMain);
  color: black;
  padding: 0.3rem 0;
}
</style>