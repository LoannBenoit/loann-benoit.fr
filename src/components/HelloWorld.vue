<template>
  <div class="hello">
    <h1>Site under construction</h1>
    <self-building-square-spinner
    class="loader"
    :animation-duration="4000"
    :size="70"
    color="#FF5E62"
/>
  </div>
</template>

<script>
import { SelfBuildingSquareSpinner  } from 'epic-spinners'
export default {
  name: 'HelloWorld',
  components: {
    SelfBuildingSquareSpinner
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.loader {
  margin: 5% auto;
}

h1 {
  margin: 10% 0 0;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
