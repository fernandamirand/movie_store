

<template>
  <div class="header">
      
      <strong class="logo">LOGO</strong>

      <div class="search-bar">
          <input type="text" class="input" placeholder="Pesquisa"/>
          <a href=""><img class="icon-search" src="../assets/search-icon.png"/></a>
          
      </div>

      <div class="links">
      <a href="" class="favoritos"><img class="heart" src="../assets/heart2.png"/></a>
      <div class="carrinho">
          🛒
          <div class="carrinho-number">
            <p>2</p>
          </div>
      </div>
      </div>
  </div> 



</template>

<style>
   *{
       margin: 0;
       padding: 0;
   } 

   .header{
       background-color: #8dd7ce; 
       height: 45px;
       display: flex;
       flex-direction: row;
       align-items: center;
       justify-content: space-between;
   }



   .logo{
       font-size: 24px;
       letter-spacing: 0.01px;
       margin-left: 40px;
       color: white;
       font-family: sans-serif;
   }

   .search-bar{
       background-color: white;
       padding: 2px;
       border-radius: 2px;
       display: flex;
       align-items: center;
       justify-content: center;
   }

   .input{
       height: 18px;
       width: 270px;
       border-radius: 4px;
       border: gray;
       padding: 5px;
   }

   .input::placeholder {
      color: #c7d0d7;
}

.input:focus{
    box-shadow: 0 0 0 0;
    border: 0 none;
    outline: 0;
} 

   .icon-search{
       width: 15px;
       align-items: center;
       padding-right: 5px;
   }


   .links{
       display: flex;
       flex-direction: row;
       margin-right: 15px;
       align-items: center;
       padding: 5px;
   }

    .carrinho {
        position: relative;
        padding: 5px;
    }

   .carrinho-number{
       width: 13px;
       height: 13px;
       border-radius: 50%;
       background-color: #fae193;
       position: absolute;
       right: 0;
       top: 0;
       color: #4f5b66;
       font-size: 10px;
       text-align: center;
      
   }


   .favoritos{
       text-decoration: none;
       
   }

   @media (max-width: 500px) {
  .header{
    background-color: #8dd7ce;
    display: flex;
    flex-direction: column;
    height: 110px;
    align-items: center;
    
    
  }

  .logo{
    padding-top: 10px;
    margin-right: 35px;

  }

  .links{
       padding-bottom: 5px;
   }

   



}



</style>