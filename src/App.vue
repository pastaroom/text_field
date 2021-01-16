<template>
  <router-link></router-link>
  <!-- <router-link to="/about">go</router-link> -->
  <!-- <router-view></router-view> -->
</template>
<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'

@Component
export default class extends Vue {
  snackbar = false;

  private form?: {} = {
    one: '',
    two: '',
    three: '',
    four: '',
    five: '',
    six: '',
    seven: '',
    eight: '',
    nine: ''
  }
  // reset
  // resetForm () {
  // }
  // submit
  // submit () {
  //   this.snackbar = true
  // }
}
</script>

<style scoped>

</style>
