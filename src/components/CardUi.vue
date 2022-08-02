<template>
<div>
  <h2 v-if="menuTitle">
    {{menuTitle}}
  </h2>
  <p v-else class="untitled">
    notitle
  </p>
  <ul>
    <li v-for="menu in menuCount" :key="menu">{{menu}}</li>
  </ul>
</div>



</template>

<script>
export default {
  props : {
    menuTitle : String,
    menuCount : Number
  }
}
</script>

<style>
.custom_input {
  padding: 20px;
  font-size: 20px;
  display: block;
  width: 100%;
  box-sizing: border-box;
  margin: 20px 0;
}
</style>