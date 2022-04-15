<template>
    <div>
        <div class="inblock">
            <ul>
                <li class="DCcomics">DC COMICS</li>
                <li>Characters</li>
                <li>Comics</li>
                <li>Movies</li>
                <li>TV</li>
                <li>Games</li>
                <li>Videos</li>
                <li>News</li>
            </ul>
            <ul>
                <li class="DCcomics">SHOP</li>
                <li>Shop DC</li>
                <li>Shop DC Collectibles</li>
            </ul>
        </div>
        <div class="inblock">
            <ul>
                <li class="DCcomics">DC</li>
                <li>Terms Of Use</li>
                <li>Privacy policy (New)</li>
                <li>ad Choices</li>
                <li>Advertising</li>
                <li>Jobs</li>
                <li>Subscriptions</li>
                <li>Talent Workshops</li>
                <li>CPSC Certificates</li>
                <li>Ratings</li>
                <li>Shop Help</li>
                <li>Contact Us</li>
            </ul>
        </div>

        <div class="inblock">
            <ul>
                <li class="DCcomics">SITES</li>
                <li>DC</li>
                <li>MAD Magazine</li>
                <li>DC kids</li>
                <li>DC Universe</li>
                <li>DC power Visa</li>
            </ul>
        </div>
        <div class="DC-bg"></div>
    </div>
</template>

<script>
export default {
  name: 'primoFooter',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

    ul{
        padding: 20px;
    }
    li{
        color: grey;
        list-style: none;
        padding: 4px;
    }

    .DCcomics{
        font-size: 25px;
        color: white;
    }

    // .DC-bg{
    //     background-image: url(../assets/dc-logo-bg.png);
    //     height: 420px;
    //     background-repeat: no-repeat;
    //     margin-left: 30%;
    // }

    .inblock{
        display: inline-block;
    }

</style>