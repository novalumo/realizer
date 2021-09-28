<!-- Please remove this file from your project -->
<template>
  <footer>
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
    <p class="text-sm mt-5">
      &copy; 2020 Realizer
    </p>
    <p class="text-xs opacity-50 mt-1">
      Promoter: Novalumo Japan G.K.
    </p>
  </footer>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
footer {
  background: #000;
  color: #eee;
  padding: 3rem;
  font-weight: bold;

  ul {
    display: flex;
    flex-direction: row;

    li {
      &:not(:last-child) {
        padding: 0 1rem 0 0;
      }

      a {
        transition: ease .2s;

        &:hover {
          opacity: .7;
        }
      }
    }
  }
}
</style>
