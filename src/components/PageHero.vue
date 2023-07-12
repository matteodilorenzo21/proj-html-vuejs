<script>
import PageHeroCard from './PageHeroCard.vue';
export default {
    components: {PageHeroCard},
    mounted() {
    // STARTING CAROUSEL AT PAGE START
    const carousel = new bootstrap.Carousel(document.getElementById('carouselExampleControls'), {
        interval: 4000,
        // AUTO SCROLL
        ride: true,
    });
              
    }
};
</script>

<template>

  <div id="hero">
      <div id="carouselExampleControls" class="carousel slide" data-bs-ride="carousel" data-bs-interval="4000">
        <div class="carousel-inner">
          <!-- FIRST IMAGE SHOWED -->
          <div class="carousel-item active">
            <img src="../assets/img/backgrounds/parallax_bredcum.jpg" class="d-block w-100" alt="Image 1">
            <div class="carousel-caption">
              <h3>INSTRUMENTAL ROCK</h3>
              <h1>MUSIC IN THIS VIDEO</h1>
              <button>READ MORE</button>
            </div>
          </div>

          <!-- SECOND IMAGE SHOWED -->
          <div class="carousel-item">
            <img src="../assets/img/backgrounds/counter_parallax.jpg" class="d-block w-100" alt="Image 2">
            <div class="carousel-caption">
              <h3>INSTRUMENTAL ROCK</h3>
              <h1>MUSIC OF THE SPIRIT</h1>
              <button>READ MORE</button>
            </div>
          </div>
        </div>

        <!-- PREV -->
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>

        <!-- NEXT -->
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>
  </div>

  <div id="hero-card">
    <PageHeroCard />
  </div>

</template>
  
  
<style lang="scss" scoped>
@import '../assets/scss/style.scss';
@import '../assets/scss/_vars.scss';
  
#hero {
    height: 750px;
}
  
img {
    max-height: 750px;
}
  
.carousel-caption {
    width: 50vw;
    position: absolute;
    top: 55%;
    left: 50%;
    transform: translate(-50%, -50%);
    text-align: center;
  
    h3 {
        color: $orange;
    }
  
    h1 {
        font-size: 80px;
    }
  
    button {
        color: $white;
        border: 1px solid $orange;
        padding: 10px 40px;
        background-color: transparent;
        transition-delay: 0.1s;

        &:hover {
            background-color: $orange;
        }
    }
}

#hero-card {
  position: absolute;
  top: 85%;
  left: 5.5%;
}
</style>
