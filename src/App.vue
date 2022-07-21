<template>
  <div id="app">
    <div>
      <main>
        <MyTitle />
        <MyHero />
      </main>
    </div>
  </div>
</template>

<script>
import MyHero from "./components/MyHero.vue"
import MyTitle from "./components/MyTitle.vue";
export default {
  name: "App",
  components: {
    MyTitle,
    MyHero,
  },
};
</script>

<style>
#app {
  color: red;
  text-align: center;
}

</style>
