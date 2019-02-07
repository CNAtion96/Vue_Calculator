<template>
  <div class="calculator">
    <div id="display"></div>
  </div>
</template>

<script>
export default {
  name: 'Calculator',
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  .calculator {
    position: absolute;
    width: 300px;
    height: 500px;
    border: 1px solid black;
    background-color: #efefef;
    top: 50%;
    left: 50%;
    margin: -250px 0 0 -150px;

    #display {
      width: 100%;
      height: 42%;
      border-bottom: 1px solid gray;
    }
  }
</style>
