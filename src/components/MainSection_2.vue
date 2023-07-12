<script>
  export default {
      methods: {
          openYouTube() {
        window.open("https://youtu.be/8LhCd1W2V0Q");
      }
    }
  };
</script>

<template>
    <section class="music-section">
      <button class="play-button" @click="openYouTube()">
        <i class="bi bi-play-fill fa-4x"></i>
      </button>
    </section>
</template>

<style lang="scss" scoped>
@import '../assets/scss/style.scss';
@import '../assets/scss/_vars.scss';

  section {
    background-image: url("../assets/img/video/Video.jpg");
    background-position: center;
    background-size: cover;
  }

  img {
    max-height: 100%;
  }

  .music-section {
    height: 500px;
    padding-top: 3%;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  
  .play-button {
    width: 100px;
    height: 100px;
    border-radius: 50%;
    font-size: 24px;
    color: $orange;
    border: 5px solid $orange;
    background-color: transparent;
    position: relative;
    cursor: pointer;

    i {
        font-size: 40px;
        position: absolute;
        top: 18px;
        left: 28px;
    }
  }
</style>