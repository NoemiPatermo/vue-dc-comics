<template>
    <div class="footer-container">
        <div class="footer-content container">
            <div class="footer-menu">
                <div class="menu-container">
                    
                    <ul>
                        <li>DC COMICS</li>
                        <li>Characters</li>
                        <li>Comics</li>
                        <li>Movies</li>
                        <li>TV</li>
                        <li>Games</li>
                        <li>Videos</li>
                        <li>News</li>
                    </ul>
    
                    <ul>
                         <li>SHOP</li>
                        <li>Shop DC</li>
                        <li>Shop DC Collectibles</li>
                    </ul>
                </div>
                <div class="menu-container">
                    <ul>
                         <li>DC</li>
                        <li>Terms of Use</li>
                        <li>Privacy policy (New)</li>
                        <li>Ad Choices</li>
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
                <div class="menu-container">
                    <ul>
                        <li>SITES</li>
                        <li>DC</li>
                        <li>MAD Magazine</li>
                        <li>DC Kids</li>
                        <li>DC Universe</li>
                        <li>DC Power Visa</li>
                    </ul>
                </div>
                 <div class="logo-container">
                    <div>
                        <img src="../assets/dc-logo-bg.png" alt="">
                    </div>
                </div>
            </div>
           
        </div>
        <div class="button-footer">
            <button>SIGN-UP NOW!</button>

            <div class="social-content">
                    <span>FOLLOW US</span>
                <img src="../assets/footer-facebook.png" alt="" />
                <img src="../assets/footer-twitter.png" alt="" />
                <img src="../assets/footer-youtube.png" alt="" />
                <img src="../assets/footer-pinterest.png" alt="" />
                <img src="../assets/footer-periscope.png" alt="" />
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Footer'
}
</script>

<style lang="scss" scoped>

        .footer-container{
            background-image: url('../assets/footer-bg.jpg');
              position: relative;
              overflow: hidden;
              
                .footer-content{
                    padding: 50px;

                .footer-menu{
                    display: flex;
                    h4{
                        color: white;
                        
                    }
                        li{
                            color:lightslategray;
                            font-size: 13px;
                            list-style: none;
                            padding: 3px;
                            margin: 15px;
                             &:first-child{
                                 font-weight: bold;
                                 color: white;
                             }
                        }
                }
                .logo-container{
                        img {
                    
                    position: absolute;
                    top: 40%;
                    left: 80%;
                    transform: translate(-100%, -50%);
                   
                    }
                }
            }
            .button-footer{
                height: 80px;
                background-color: #191919;
                display: flex;
                justify-content: space-around;
                align-items:center ;
                
                    button{
                        background-color: #303030;
                        color: white;
                        border: 1px solid blue;
                        height: 60px;
                        padding: 10px;
                    }

            }
                .social-content{
                
                    span{
                        color: blue;
                        font-size: 15px;
                        
                    }
                    img{
                        padding: 10px;
                        vertical-align: middle;
                    }
                }
            
        }
    
</style>