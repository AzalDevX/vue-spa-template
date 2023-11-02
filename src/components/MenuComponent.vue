<template>
    <header class="menu">
    <img alt="OoI" class="logo" src="@/assets/favicon.png" width="125" height="125" />
        <nav class="nav">
            <RouterLink to="/">Home</RouterLink>
            <RouterLink to="/about">About</RouterLink>
        </nav>
    </header>
</template>

<script>
import { RouterLink } from 'vue-router'

export default {
  components: {
    RouterLink,
  },
  created() {},
  mounted(){},
  data() {
    return {}
  },
  methods: {},
  computed: {},
};
</script>

<!-- 👇 Delete the code below 👇 -->
<style>
  .menu{
    display: flex;
    justify-content: space-evenly;
    align-items: center;
    width: 100vw;
    font-size: 3rem;
    background-color: #222;
  }

  .nav{
    width: 70%;
    display: flex;
    justify-content: space-evenly;
  }

  .nav a{
    text-decoration: none;
    color: white;
  }

  .nav a:hover{
    color: grey;
  }
</style>