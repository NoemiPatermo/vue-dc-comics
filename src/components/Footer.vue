<template>
    <div class="footer-container ">
        <div class="footer-login">
            <button>SIGN-UP NOW!</button>
        </div>
        <div class="footer-content">
            <span>FOLLOW US</span>
            <div class="footer-icon">
                <img src="../assets/footer-facebook.png" alt="">
                <img src="../assets/footer-twitter.png" alt="">
                <img src="../assets/footer-youtube.png" alt="">
                <img src="../assets/footer-pinterest.png" alt="">
                <img src="../assets/footer-periscope.png" alt="">
            </div>
            
        </div>
        
    </div>
</template>

<script>
export default {
    name:'Footer'
}
</script>

<style lang="scss" scoped>
    .footer-container{
        height: 80px;
        background-color: #191919;
        display: flex;
        justify-content: space-around;
        align-items: center;
            
    
    
        .footer-login button{
           margin-top: 10px;
           color: white;
           background-color: #191919;
           width: 100px;
           padding: 5px;
           border: 1px solid blue;
        }
        .footer-content{
            
            
            span{
                color: blue;
                font-size: 15px;
            }
            img{
                padding: 5px;
            }
        }
    }

</style>