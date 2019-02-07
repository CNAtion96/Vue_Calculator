<template>
  <div class="calculator">
    <Display  />
  </div>
</template>

<script>
import Display from './Display';

export default {
  name: 'Calculator',
  components: {
    Display,
  }
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
  }
</style>
