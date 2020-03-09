<template>
  <div class="container" align="center">
    <a href="#a" style="font-size: 60px;">
      url anchor #a
    </a>

    <div style="margin-top: 20px;">
      <p>expected: http://localhost:3000/test/my/all#a</p>
      <p>actually: http://localhost:3000/test/#a</p>
    </div>
  </div>
</template>

<script>
export default {
}
</script>

<style lang='less'>
</style>
