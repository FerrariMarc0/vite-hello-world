<script>
  import AppTitleVue from "./components/AppTitle.vue";
  import AppHeroVue from "./components/AppHero.vue";
  export default {
    components: {
      AppTitleVue,
      AppHeroVue
    }
  }
</script>

<template>
    <AppTitleVue></AppTitleVue>
    <AppHeroVue></AppHeroVue>
</template>

<style>
*{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}
body{
    background-color: black;
    display: flex;
    justify-content: center;
    font-family: sans-serif;
}
.container{
    margin-top: 3.125rem;
    line-height: 6.25rem;
    color: red;
}
</style>