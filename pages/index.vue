<template>
  <div :class="$style.main">
    <h1>helow world!</h1>
    <a href="#">click me</a>
    <a href="#">click me</a>
    <a href="#">click me</a>
    <a href="#">click me</a>
    <a href="#">click me</a>
    <a href="#">click me</a>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss" module>
.main {
  width: 100%;
  background: #165432;
  height: 400px;
  h1 {
    font-size: 40px;
    color: #fff;
    text-align: center;
  }
}
a {
  font-size: 35px;
  color: blue;
  text-align: center;
}
</style>
