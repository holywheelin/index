<template>
  <div>
    <header>
     <ul>
      <!--h1>HollyWheelin'</h1-->
	  <img src="/holywheelin_logo.png"
	  width="10%"
	  >
	  <nav>
	    <li>
          <nuxt-link to="/inspire">Home</nuxt-link>
        </li>
	    <li>
          <nuxt-link to="/about">about</nuxt-link>
        </li>
	  </nav>
      <!--HeaderNav /-->
	 </ul>
    </header>
  </div>
</template>
<script>
  import HeaderNav from "@/components/headerNav.vue";
  export default {
      components: {
      HeaderNav
    }
  };
</script>
<style lang="scss" scoped>
header {
  color: #fff;
  padding: 5px;
  background-color: #527b8e;
}
</style>
