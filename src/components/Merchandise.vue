<template>
    <div class="merchandise-container">
        <div class="container">
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
                <span>SUBSCRIPTION</span>
            </div>
            <div>
                <img src="../assets/buy-comics-shop-locator.png" alt="">
                <span>COMIC SHOP LOCATOR</span>
            </div>
            <div>
                <img src="../assets/buy-dc-power-visa.svg" alt="">
                <span>CD POWER VISA</span>
            </div>
        
        </div>

    </div>
</template>

<script>
export default {
    name: 'Merchandise'
}
</script>

<style lang="scss" scoped>
    .merchandise-container{
        background-color: blue;
        height: 150px;
        
        
         .container{
               display: flex;
                justify-content: space-between;
                align-items: center;
                div{
                    display: flex;
                    align-items: center;
                    img{
                 width: 50px;
                 margin-top: 13px;
                  &:nth-last-child(4){
                         width: 30px;
                     }
                
                     }
                }
             span{
                 color: white;
                 font-size: 12px;
                 padding-left: 10px;
                
             }
         }
    }
</style>