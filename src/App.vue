<script>
import PageHeader from './components/PageHeader.vue';
import PageHero from './components/PageHero.vue';
import PageMain from './components/PageMain.vue';
export default {
  components: {PageHeader, PageHero, PageMain},
};
</script>

<template>
<PageHeader />
<PageMain />
</template>

<style lang="scss" scoped>
@import './assets/scss/style.scss';
@import './assets/scss/_vars.scss';

</style>
