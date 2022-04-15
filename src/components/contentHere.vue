<template>
  <div class="content-here">
   <h1 class="content">&lt;&hyphen;&hyphen; Content goes here &hyphen;&hyphen;&gt;</h1>
  </div>
</template>

<script>
export default {
  name: 'contentHere',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

    .content-here{
        background-color: black;
    }
    .content{
        color: white;
        padding: 60px;
    }
</style>