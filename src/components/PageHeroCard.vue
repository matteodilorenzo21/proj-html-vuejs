<script>
export default {

};
</script>

<template>
    <div class="container-fluid">
        <div class="row d-flex justify-content-center">

            <div class="col-3 text-center">
                <img src="../assets/img/hero/speaker.svg" alt="speaker">
                <h1 class="fs-3">ORIGINAL IDEAS</h1>
                <p>Contrary Popular Belief, Lorem Ipsum Not Simply Ipsum Random Text.</p>
            </div>

            <div class="col-3 text-center">
                <img src="../assets/img/hero/disc.svg" alt="disc">
                <h1 class="fs-3">MUSIC STUDIO</h1>
                <p>Contrary Popular Belief, Lorem Ipsum Not Simply Ipsum Random Text.</p>
            </div>

            <div class="col-3 text-center">
                <img src="../assets/img/hero/headphones.svg" alt="headphones">
                <h1 class="fs-3">ACOUSTIC COVERS</h1>
                <p>Contrary Popular Belief, Lorem Ipsum Not Simply Ipsum Random Text.</p>
            </div>

        </div>
    </div>
</template>

<style lang="scss" scoped>
@import '../assets/scss/style.scss';
@import '../assets/scss/_vars.scss';

.col-3 {
    height: 350px;
    width: 420px;
    background-color: rgb(20, 20, 20);
    margin: 0 15px;
    padding-inline: 30px;

    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

img {
    max-height: 120px;
    padding-bottom: 15px;
    filter: brightness(0) invert(1);
    transition: filter 0.4s ease-in-out;
    cursor: pointer;

    &:hover {
        filter: brightness(1) invert(0.6) sepia(20) saturate(30);
    }
}

h1 {
    color: $white;
}

p {
    font-family: 'Arial', 'sans-serif';
    color: $white;
}
</style>