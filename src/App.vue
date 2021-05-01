<template>
  <h1>Hello App!</h1>
  <p>
    <router-link to="/">Go to Home</router-link>
    <router-link to="/contact">Go to Contact</router-link>
  </p>
  <el-button type="primary">Element UI</el-button>
  <router-view></router-view>
</template>

<script lang="ts">

export default ({
  name: 'App',
})
</script>

<style lang="scss">
  body{
    border: 1px solid red;
  }
</style>
