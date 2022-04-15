<template>
  <div class="nav-bar">
    <ul>
      <li>CHARACTERS</li>
      <li>COMICS</li>
      <li>MOVIES</li>
      <li>TV</li>
      <li>GAMES</li>
      <li>COLLECTIBLES</li>
      <li>VIDEOS</li>
      <li>FANS</li>
      <li>NEWS</li>
      <li>SHOP</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'navBar',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  li{
    list-style: none;
    display: inline-block;
    padding: 20px; 

  }

  li:hover{
    color:#409fff ;
    cursor: pointer;
    border-bottom: 4px solid #409fff;
    height: 109px;
  }
</style>
