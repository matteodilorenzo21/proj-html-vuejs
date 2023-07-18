<script>
export default {
  
};
</script>

<template>

    <section class="pt-5 text-white">
      <h3>WHO WE ARE</h3>
      <h1>SENSE THE JAZZ</h1>
  
      <div class="card-row row row-cols-1 row-cols-md-2 row-cols-lg-3 justify-content-center">

      <div class="col my-3">
        <div class="card">
          <img src="../assets/img/gallery/gallery1.jpg" alt="gallery">
        </div>
        <div class="mb-5">
          <h5 class="card-title">A ROLL AND BANG THE FLOOR</h5>
          <p class="card-text">Stream on: 
            <span><i class="fab fa-spotify"></i></span>
            <span><i class="fa-brands fa-youtube"></i></span>
            <span><i class="fa-solid fa-music"></i></span>
            <span><i class="fa-brands fa-soundcloud"></i></span>
            <span><i class="fa-regular fa-compass"></i></span>
          </p>
        </div>
      </div>

      <div class="col my-3">
        <div class="card">
          <img src="../assets/img/gallery/gallery2.jpg" alt="gallery">
        </div>
        <div class="mb-5">
          <h5 class="card-title">YOUR MELODY TO OUR MUSIC</h5>
          <p class="card-text">Stream on: 
            <span><i class="fab fa-spotify"></i></span>
            <span><i class="fa-brands fa-youtube"></i></span>
            <span><i class="fa-solid fa-music"></i></span>
            <span><i class="fa-brands fa-soundcloud"></i></span>
            <span><i class="fa-regular fa-compass"></i></span>
          </p>
        </div>
      </div>

      <div class="col my-3">
        <div class="card">
          <img src="../assets/img/gallery/gallery3.jpg" alt="gallery">
        </div>
        <div class="mb-5">
          <h5 class="card-title">TOUCHING HEAVEN ON FREQUENCY</h5>
          <p class="card-text">Stream on: 
            <span><i class="fab fa-spotify"></i></span>
            <span><i class="fa-brands fa-youtube"></i></span>
            <span><i class="fa-solid fa-music"></i></span>
            <span><i class="fa-brands fa-soundcloud"></i></span>
            <span><i class="fa-regular fa-compass"></i></span>
          </p>
        </div>
      </div>

      <div class="col my-3">
        <div class="card">
          <img src="../assets/img/gallery/gallery4.jpg" alt="gallery">
        </div>
        <div class="mb-5">
          <h5 class="card-title">MUSIC MAKES STRONGE BEATS</h5>
          <p class="card-text">Stream on: 
            <span><i class="fab fa-spotify"></i></span>
            <span><i class="fa-brands fa-youtube"></i></span>
            <span><i class="fa-solid fa-music"></i></span>
            <span><i class="fa-brands fa-soundcloud"></i></span>
            <span><i class="fa-regular fa-compass"></i></span>
          </p>
        </div>
      </div>

      <div class="col my-3">
        <div class="card">
          <img src="../assets/img/gallery/gallery5.jpg" alt="gallery">
        </div>
        <div class="mb-5">
          <h5 class="card-title">SOUND IS THE SPARK OF TIME</h5>
          <p class="card-text">Stream on: 
            <span><i class="fab fa-spotify"></i></span>
            <span><i class="fa-brands fa-youtube"></i></span>
            <span><i class="fa-solid fa-music"></i></span>
            <span><i class="fa-brands fa-soundcloud"></i></span>
            <span><i class="fa-regular fa-compass"></i></span>
          </p>
        </div>
      </div>

      <div class="col my-3">
        <div class="card">
          <img src="../assets/img/gallery/gallery6.jpg" alt="gallery">
        </div>
        <div class="mb-5">
          <h5 class="card-title">MAKE YOUR NIGHT GROOVY</h5>
          <p class="card-text">Stream on: 
            <span><i class="fab fa-spotify"></i></span>
            <span><i class="fa-brands fa-youtube"></i></span>
            <span><i class="fa-solid fa-music"></i></span>
            <span><i class="fa-brands fa-soundcloud"></i></span>
            <span><i class="fa-regular fa-compass"></i></span>
          </p>
        </div>
      </div>

      </div>

    </section>
</template>
  
<style lang="scss" scoped>
@import '../assets/scss/style.scss';
@import '../assets/scss/_vars.scss';

  section {
    text-align: center;
    padding: 20px;
  }
  
  h3 {
    margin: 10px 0;
    color: $orange;
  }

  h1 {
        font-size: 70px;
        font-family: 'Anton', 'sans-serif';
        padding-bottom: 30px;
  }
  
  .card {
    width: 100%;
    height: 450px;
    border-radius: 0;
    border: none;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
  }
  
  .card img {
    min-height: 100%;
    max-width: 100%;
    object-fit: cover;
  }
  
  .card-title {
    margin-top: 10px;
    font-size: 30px;
  }

  span {
    padding-inline: 8px;
  }
</style>