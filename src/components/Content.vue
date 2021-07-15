<template>
  <nav></nav>
  <main>
    <div :class="{ page: whoAmILong }">
      <WhoAmILong />
    </div>
    <div>
      <WhoAmI />
      <div class="divider"></div>
      <MyProjects />
      <div class="divider"></div>
      <UtilityBelt />
      <div class="divider"></div>
      <Scientist />
      <Footer />
    </div>
  </main>
</template>

<script>
import Footer from "./Footer.vue";
import WhoAmI from "./sections/WhoAmI.vue";
import WhoAmILong from "./sections/WhoAmILong.vue";
import MyProjects from "./sections/MyProjects.vue";
import UtilityBelt from "./sections/UtilityBelt.vue";
import Scientist from "./sections/Scientist.vue";

export default {
  components: {
    WhoAmI,
    WhoAmILong,
    MyProjects,
    UtilityBelt,
    Scientist,
    Footer,
  },
  data() {
    return {
      teste: "oioi",
      whoAmILong: false,
    };
  },
  mounted() {
    setInterval(() => {
      this.whoAmILong = window.location.hash === "#sobre";
    }, 200);
  },
};
</script>

<style>
div.divider {
  max-width: 600px;
  border: 1px var(--colorMain) solid;
  margin: 0 auto;
}
Section p {
  text-indent: 1.5rem;
  line-height: 1.9rem;
}

main > div:first-child {
  position: absolute;
  width: 100vw;
  right: -100%;
  transition-duration: 0.7s;
}

main > div.page:first-child {
  right: 0;
}

main > div.page + div {
  display: none;
}
</style>