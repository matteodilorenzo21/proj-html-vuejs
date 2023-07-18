<script>
export default {

};
</script>

<template>

    <section class="p-5">

        <div class="container p-5 text-white mt-5">
            <h3 class="mt-5">INSTRUMENTAL ROCK</h3>
            <h1>ALBUM OUT NOW</h1>
            <button>READ MORE</button>
        </div>

    </section>

</template>

<style lang="scss" scoped>
@import '../assets/scss/style.scss';
@import '../assets/scss/_vars.scss';

section {
    height: 650px;
    background-image: url("../assets/img/backgrounds/parallax_bredcum.jpg");
    background-position: center;
    background-size: cover;

    h3 {
        color: $orange;
    }

    h1 {
        font-size: 120px;
    }

    button {
      color: $white;
      border: 1px solid $orange;
      padding: 15px 50px;
      background-color: transparent;
      transition-delay: 0.1s;
    
      &:hover {
        background-color: $orange;
      }
    }
}

</style>