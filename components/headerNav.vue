<template>
  <div>
    <nav>
      <ul>
        <li>
          <nuxt-link to="/inspire">Home</nuxt-link>
        </li>
        <li>
          <nuxt-link to="/inspire">About</nuxt-link>
        </li>
        <li>
          <nuxt-link to="/about">History</nuxt-link>
        </li>
        <li>
          <nuxt-link to="/link04">Contact</nuxt-link>
        </li>
      </ul>
    </nav>
  </div>
</template>
<script>
  export default {
    components: {}
  };
</script>
<style lang="scss" scoped>
nav {
  color: #fff;
    ul {
      display: flex;
      justify-content: flex-end;
      li {
        list-style-type: none;
        margin-left: 15px;
        a {
          color: #fff;
        }
      }
    }
}
</style>
