<template>
  <header>
    <nuxt-link to="">
      <img src="~/assets/img/logo.svg" alt="logo" width="120px">
    </nuxt-link>
    <ul>
      <li>
        <a href="/#about">
          About
        </a>
      </li>
      <li>
        <a href="/#join">
          Join
        </a>
      </li>
    </ul>
  </header>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
header {
  background: transparent;
  color: #f8f9fa;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  padding: 1rem 1.25rem;
  position: fixed;
  top: 0;
  width: 100%;
  z-index: 10;

  a {
    transition: ease .2s;

    &:hover {
      opacity: .5;
    }
  }

  ul {
    display: flex;
    flex-direction: row;
    font-size: 1.25rem;
    letter-spacing: .1rem;

    li {
      &:not(:last-child) {
        padding: 0 1.5rem 0 0;
      }
    }
  }
}
</style>
