<template>
  <div>
    <h1>hi</h1>
    <hr />
    <card-ui :menuTitle="'test'" :menuCount="5"/>
    <card-ui />
    <card-ui />
    <card-ui />
  </div>
  

</template>

<script>
import CardUi from './components/CardUi.vue'
export default {
  components : {
    CardUi
  }
}
</script>

<style>

</style>