<template>
<div>
  <header1 />
  <main1 />
  <footer1 />
</div>
</template>

<script>
import header1 from '@/components/header.vue';
import main1 from "@/components/main.vue";
import footer1 from "@/components/footer.vue";

export default {
  name: "App",
  components: {
    header1,
    main1,
    footer1,
  },
  data() {
    return{
      recipesData: [
        {id: 1, name: 'рецепт 1', descriprion: 'описание рецепта 1'},
        {id: 2, name: 'рецепт 2', descriprion: 'описание рецепта 2'},
        {id: 3, name: 'рецепт 3', descriprion: 'описание рецепта 3'}
      ]
    }
  }
};
</script>
<style>
@import 'styles/style.css';
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
