<template>
  <div class="Display">
    <p></p>
  </div>
</template>

<script>
export default {
  name: 'Display',
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  .Display {
      background-color: white;
      width: 100%;
      height: 42%;
      border-bottom: 1px solid lightgray;
      margin: 0px;
      text-align: right;
      font-size: 60px;
      padding-top: 11%;

      p {

          height: 100%;
          vertical-align: center;
          margin:0px;
          padding: 10px;
      }
  }
</style>