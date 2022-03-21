<template>
  <div class="home">
    <section class="hero is-dark">
      <div class="hero-body">
        <div class="container">
          <h1 class="title">Welcome to uReviews</h1>
          <h2 class="subtitle">
            Check out recent posts below
          </h2>
          <div class="button-block">
            <button class="button is-xl is-dark">
              Sign Up to Browse Posts
            </button>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: 'HomeView',
  components: {},
};
</script>

<style lang="scss" scoped>
.hero {
  text-align: center;
  background-image: url("https://img.wallpapersafari.com/desktop/1680/1050/70/63/G85NOx.png");
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  height: 400px;
}
.hero-body .title {
  padding: 40px 0 20px 0;
  font-size: 60px;
  color: antiquewhite;
}
.subtitle {
  font-size: 30px;
  color: antiquewhite;
}
.button-block {
  text-align: center;
  margin-left: auto;
  margin-right: auto;
  width: 100%;
  position: absolute;
  bottom: -150px;
  .button {
    margin-right: 50px;
    padding-left: 50px;
    padding-right: 50px;
  }
  .welcome {
    width: 400px;
    padding: 10px;
    margin-left: auto;
    margin-right: auto;
  }
}
.is-xl {
  font-size: 1.7rem;
}
</style>
