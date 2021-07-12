<template>
    <div class="header-container">
      <nav class="nav-container">

            <div class="logo-container">
                <img src="../assets/dc-logo.png" alt="">
            </div>
      
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
        </nav>
    </div>
</template>

<script>
export default {
    name:'Header'
}
</script>


<style lang="scss" scoped>
  .header-container{
      width: 1200px;
    
      .nav-container {
          display: flex;
          justify-content: space-between;
          align-items: center;
         

        ul{
            display: flex;
            list-style: none;
            align-items: center;
            justify-content: space-between;
        
            li{
                padding: 15px;
                font-weight: bold;

                &:hover{
                    border-bottom: 1px solid blue;
                    cursor: pointer;
                }
            }
        }
      }
     
  }

</style>