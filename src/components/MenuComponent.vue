<template>
    <header>
    <img alt="OoI" class="logo" src="@/assets/favicon.png" width="125" height="125" />
        <nav>
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