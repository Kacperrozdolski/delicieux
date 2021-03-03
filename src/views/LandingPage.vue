<template>
  <div class="landing">
    <main-header></main-header>
    <main-hero></main-hero>
  </div>
</template>

<script>
import MainHeader from "@/components/MainHeader.vue";
import MainHero from "@/components/MainHero.vue";
export default {
  components: {
    MainHeader,
    MainHero
  },
};
</script>

<style lang="scss" scoped>
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800;900&display=swap");
.landing {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  font-family: Poppins;
}
</style>