<template>
  <header>
    <img src="~/assets/img/example_logo.png" alt="logo" width="120px">
    <ul>
      <li>
        <nuxt-link to="">
          Home
        </nuxt-link>
      </li>
      <li>
        <nuxt-link to="">
          About
        </nuxt-link>
      </li>
      <li>
        <nuxt-link to="">
          Join
        </nuxt-link>
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
  // background: linear-gradient(30deg, #123, #456, #789);
  background: #323b4e;
  color: #f8f9fa;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  padding: .75rem 1rem;

  ul {
    display: flex;
    flex-direction: row;

    li:not(:last-child) {
      padding: 0 1rem 0 0;
    }
  }
}
</style>
