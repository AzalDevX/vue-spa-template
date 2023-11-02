<template>
  <MenuComponent/>
  
  
  <RouterView />
</template>



<script>
import { RouterView } from 'vue-router'
import MenuComponent from '@/components/MenuComponent.vue'

export default {
  components: {
    RouterView,
    MenuComponent
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
