<!-- Please remove this file from your project -->
<template>
  <footer>
    <ul>
      <li>
        <nuxt-link to="">
          Home
        </nuxt-link>
      </li>
      <li>
        <nuxt-link to="">
          Home
        </nuxt-link>
      </li>
      <li>
        <nuxt-link to="">
          Home
        </nuxt-link>
      </li>
      <li>
        <nuxt-link to="">
          Home
        </nuxt-link>
      </li>
    </ul>
    <p class="text-sm mt-5">&copy; 2020 Realizer</p>
  </footer>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
footer {
  border-top: solid 1px #ccc;
  color: #777;
  padding: 3rem;

  ul {
    display: flex;
    flex-direction: row;

    li {
      &:not(:last-child) {
        padding: 0 1rem 0 0;
      }
    }
  }
}
</style>
