<template>
    <div class="main-container">
        <div class="main-content">
            Content goes here
        </div>
        <div class="icon-container">
            <div>
                <img src="../assets/buy-comics-digital-comics.png" alt="">
                <span>DIGITAL COMICS</span>
            </div>
            <div>
                <img src="../assets/buy-comics-merchandise.png" alt="">
                <span>DC MERCHANDISE</span>
            </div>
            <div>
                <img src="../assets/buy-comics-subscriptions.png" alt="">
                <span>SUBSCRITPION</span>
            </div>
            <div>
                <img src="../assets/buy-comics-shop-locator.png" alt="">
                <span>COMIC SHOP LOCATOR</span>
            </div>
            <div>
                <img src="../assets/buy-dc-power-visa.svg" alt="">
                <span>DC POWER VISA</span>
            </div>
            
        </div>
        
    </div>
</template>

<script>
export default {
    name:'Main'
}
</script>

<style lang="scss" scoped>

    .main-container{
        height: 500px;

        .main-content{
            height: 150px;
            background-color: black;
            color: white;
        }
        .icon-container{
            height: 150px;
            background-color: blue;
            display: flex;
            justify-content: space-around;
            align-items: center;
            img{
                width: 30px;
            }
            span{
                color: white;
                font-size: 12px;
            }
        }

    }

</style>