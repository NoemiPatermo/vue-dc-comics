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
            </div>
            <div class="logo-container">
                <div>
                    <img src="../assets/dc-logo-bg.png" alt="">
                </div>
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
                    height: 500px;
                    position: absolute;
                    top: 50%;
                    transform: translate(-100%, -50%);
                    }
                }
            }
        }
    
</style>