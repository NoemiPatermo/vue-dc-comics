<template>
    <div class="header-container container">
      <nav class="nav-container container">

            <div class="logo-container">
                <img src="../assets/dc-logo.png" alt="">
            </div>
            <!--ciclo con il v-for per stampare la mia nav, usa la chiave per identificae attributo univoco-->
            <ul>
                <li v-for="element in menuLinks" :key="element.id">
                   <a href="#">{{element.name}}</a> 
                </li>
            </ul>
          <!--  <ul>
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
            </ul>-->
        </nav>
    </div>
</template>

<script>
export default {

    name:'Header',
    
    data: function() {  //appena viene caricato il componente, viene lanciata subito la funzione per poter generare il data
                            //che ti torna un oggetto
        return{
            menuLinks:[
            {
                id: 0,
                name: 'CHARACTERS',
            },
            {
                id: 1,
                name: 'COMICS',
            },
            {
                id: 2,
                name:'MOVIES',
            },
            {
                id: 3,
                name:'TV',
            },
            {
                id: 4,
                name: 'GAMES',
            },
            {
                id: 5,
                name: 'COLLECTIBLES',
            },
            {
                id: 6,
                name: 'VIDEOS',
            },
            {
                id: 7,
                name: 'FANS',
            },
            {
                id: 8,
                name: 'NEWS',
            },
            {
                id: 9,
                name: 'SHOP',
            },
        ]
    }
        
 },     
    
};
</script>


<style lang="scss" scoped>
  .header-container{
      
    
      .container {
          display: flex;
          justify-content: space-between;
          align-items: center;
          
          .logo-container{
              img{
                  width: 70px;
              }
          }
         

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
                a{
                    text-decoration: none;
                    color: black;
                }
            }
        }
      }
     
  }

</style>