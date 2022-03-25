<template>
  <div class="hero">
    <section class="jumbotron">
      <h1>{{ msg }}</h1>
    </section>
  </div>
</template>

<script>
export default {
  name: "HeoJumbo",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.jumbotron {
  background-color: lightblue;
  padding: 2rem;
  width: 70%;
  margin: 2rem auto;
}
</style>
