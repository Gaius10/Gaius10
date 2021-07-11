<template>
  <ul class="socialLinks">
    <li>
      <a target="_blank" href="https://www.instagram.com/caiu.correa/">
        <i class="fab fa-instagram"></i>
        caiu.correa
        <i class="fas fa-external-link-alt"></i>
      </a>
    </li>
    <li>
      <a target="_blank" href="https://www.linkedin.com/in/caio-corrêa-chaves/">
        <i class="fab fa-linkedin"></i>
        Caio Corrêa Chaves
        <i class="fas fa-external-link-alt"></i>
      </a>
    </li>
    <li>
      <a target="_blank" href="https://github.com/Gaius10">
        <i class="fab fa-github"></i>
        Gaius10
        <i class="fas fa-external-link-alt"></i>
      </a>
    </li>
  </ul>
</template>

<script setup>
</script>

<style>
ul.socialLinks {
  width: 100%;
  display: flex;
  flex-direction: column;
  gap: 0.2rem;
}

ul.socialLinks li {
  display: block;
}

ul.socialLinks li a {
  /* background: #252525; */
  background-color: var(--colorDocumentSecondary);
  color: black;
  display: block;
  padding: 1rem 0;
  border-radius: 1rem;
}

@media only screen and (min-width: 1200px) {
  ul.socialLinks li a {
    transition-duration: 0.4s;
    cursor: pointer;
  }
  ul.socialLinks li a:hover {
    background-color: #bbb;
  }
}
</style>