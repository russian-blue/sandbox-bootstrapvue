<template>
  <div class="text-center my-3">
    <b-button v-b-popover.hover="'I am popover content!'" title="Popover Title">Hover Me</b-button>
  </div>
</template>

<script>
import 'bootstrap/dist/css/bootstrap.css'
import 'bootstrap-vue/dist/bootstrap-vue.css'


export default {
  name: 'BootstrapSample',
  props: {}
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
</style>
