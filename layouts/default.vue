<template>
  <div>
    <el-button type="primary">Primary Button</el-button>
    <nuxt/>
  </div>
</template>

<script>
  import { Button } from 'element-ui'
  export default {
    components: {
      'el-button': Button
    }
  }
</script>

<style>
  * {
    font-family: "Helvetica Neue",Helvetica,Arial,sans-serif;
  }
  html, body {
    margin: 0;
    padding: 0;
  }
</style>
