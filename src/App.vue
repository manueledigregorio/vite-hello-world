<template>
   <AppTitle />
   <AppHero />
</template>

<script>
import AppHero from './components/AppHero.vue';
import AppTitle from './components/AppTitle.vue';
export default {
  name:'App',
  components: {
    AppTitle,
    AppHero
  }
}
</script>

<style>

</style>