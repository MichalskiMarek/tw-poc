<template>
  <div class="home">
    <NavBar msg="Welcome to Your Vue.js + TypeScript App"/>
  </div>
</template>

<script lang="ts">
import {Options, Vue} from 'vue-class-component';
import NavBar from '@/components/NavBar.vue';

@Options({
  components: {
    NavBar,
  },
})
export default class Home extends Vue {
}
</script>
