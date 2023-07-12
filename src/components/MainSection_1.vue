<script>
export default {
  data() {
    return {
      title: "SENSE THE JAZZ",
      subtitle: "WHO WE ARE",
      description:
        "The Story Of Jazz And Blues Society Is The Story Of Determination, Passion, Idealism, Community, And Of Course, Music. Founded In 1985 And Incorporated In 1986, As A Community Based, Not-For-Profit, Charitable Arts Organization Located In Vancouver, British Columbia, The Society, From The Very Beginning, Has Worked Diligently To Establish Vancouver As A Centre For The Creation And Exchange Of Sounds And Ideas Between The Local, National And International Music Communities."
    };
  }
};
</script>

<template>
  <section>
    <div class="container-fluid text-white text-center">
      <h3>{{ subtitle }}</h3>
      <h1>{{ title }}</h1>
      <p>{{ description }}</p>
      <button>READ MORE</button>
    </div>
  </section>
</template>

<style lang="scss" scoped>
@import '../assets/scss/style.scss';
@import '../assets/scss/_vars.scss';

section {
    margin-top: 300px;
    height: 500px;

    h3 {
        color: $orange;
    }

    h1 {
        font-size: 70px;
        font-family: 'Anton', 'sans-serif';
    }

    p {
        font-size: 16px;
        font-family: 'Arial', 'sans-serif';
        padding: 20px 300px;
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