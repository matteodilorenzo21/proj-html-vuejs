<script>
import PageHero from './PageHero.vue';
export default {
components: {PageHero},
};
</script>

<template>
 <header class="px-5">
    <div class="d-flex justify-content-between align-items-center h-100">

        <!-- HEADER LOGO -->
        <div>
            <a href="#"><img src="../../public/Logo.png" alt="logo"></a>
        </div>

        <!-- HEADER NAVBAR -->
        <div>
            <ul class="d-flex pt-3">
               <li><a href="#">HOME</a></li>
               <li><a href="#">BLOG</a></li>
               <li><a href="#">EVENTS</a></li>
               <li><a href="#">GALLERY</a></li>
               <li><a href="#">ABOUT US</a></li>
               <li><a href="#">CONTACT US</a></li>
               <li><a href="#">SHOP</a></li>
               <li><a href="#"><i class="bi bi-search"></i></a></li>
            </ul>
        </div>
    </div>
 </header>
 <PageHero />
</template>

<style lang="scss" scoped>
@import '../assets/scss/style.scss';
@import '../assets/scss/_vars.scss';

header {
  height: 100px;
  background-color: $black;
  position: fixed;
  right: 0;
  left: 0;
  top: 0;
  z-index: 2;
  box-shadow: 0px 1px 10px 0px rgba(255, 255, 255, 0.2);
}

li {
    margin: 0 22px;

    a {
        color: $white;
        font-size: 18px;

        &:hover {
            color: $orange;
        }
    }
}

</style>