<template>
  <div class="slidmenu">
    <header>
    </header>
  </div>
</template>

<script>
export default {
  name: 'SideMenu',
  props: {  
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h3 {
  margin: 40px 0 0;
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
header{
    padding:20px;
    background:black;
    height:100%
}
</style>
