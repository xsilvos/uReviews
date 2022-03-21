<template>
  <nav class="navbar container" role="navigation" aria-label="main navigation">
    <div class="navbar-brand">

      <a class="navbar-item" href="/">
        <img src="@/assets/logo.png">
      </a>
      <a
          role="button"
          class="navbar-burger burger"
          aria-label="menu"
          aria-expanded="false"
          data-target="navbarBasicExample"
      >
        <span aria-hidden="true"></span>
        <span aria-hidden="true"></span>
        <span aria-hidden="true"></span>
      </a>
    </div>
    <div id="navbar" class="navbar-menu">
      <div class="navbar-start">
        <router-link to="about" class="navbar-item">About</router-link>
      </div>
      <div class="navbar-end">
        <div class="navbar-item">
          <div class="buttons">
            <a class="button is-dark">
              <strong>Sign In</strong>
            </a>
          </div>
        </div>
      </div>
    </div>
  </nav>
</template>
<script>
export default {
  name: 'uNav',
};
</script>

<style lang="scss" scoped>
nav {
  display: flex;
  flex-direction: row;
  padding: 12px;
  width: 90%;
  margin: 0 auto;
  @media(min-width: 1140px) {
    max-width: 1140px;
  }

  a {
    font-weight: bold;
    color: darkred;
    text-decoration: none;
    &.router-link-exact-active {
      color: #d88d00;
    }
  }
}

img {
  align-items: flex-start;
  width: 200px;
  transition: 0.5s ease all;
}
</style>