<template>
  <div class="bg-color">
   <ul>
        <li><img class="logo" src="../assets/buy-comics-digital-comics.png"></li>
        <p class="p">DIGITAL COMICS</p>
        <li><img class="logo" src="../assets/buy-comics-merchandise.png"></li>
        <p class="p">DC MERCHANDISE</p>
        <li><img class="logo" src="../assets/buy-comics-subscriptions.png"></li>
        <p class="p">SUBSCRIPTION</p>
        <li><img class="logo" src="../assets/buy-comics-shop-locator.png"></li>
        <p class="p">COMIC SHOP LACATOR</p>
        <li><img class="logo-svg" src="../assets/buy-dc-power-visa.svg"></li>
        <p class="p">DC POWER VISA</p>
</ul>
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

    .bg-color{
        background-color: #0080ff;
        text-align: center;
    }

    .content{
        color: white;
        padding: 60px;
    }

    .logo-svg{
        width: 80px;
    }

    li{
       display: inline-block; 
       vertical-align: middle;
       padding: 30px;
       padding-left:50px ;
    }

    .logo{
        width: 80px;
    }

    p{
        display: inline-block;
        color: white;
        margin-left:-20px ;
    }
</style>