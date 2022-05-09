<template>
<div class="all">
     <div class="movie-card">
         <div class="movie-img">
                <img class="heart" src="../assets/heart2.png"/>
                <h5 class="date">7 de Janeiro de 2019</h5>
         </div>
         <div class="bottom-container">
             <div class="infos">
                <h4>Doctor Strange</h4>
                <div class="details">
                    <div class="stars">
                    <h5>⭐</h5>
                    <h4>7</h4>
                    </div>
                    <p class="genero">Gênero</p>
                </div>
                <span class="price">R$79,99</span>
             </div>
         </div>
         <button class="button">Adicionar</button>
     </div>
</div>
</template>




<script>
</script>
   


<style>

.all {
    display: flex;
    align-items: center;
}

.movie-card {
    margin-top: 20px;
    margin-left: 50px;
    margin-right: 30px;
    width: 210px;
    height: 310px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    box-shadow: 10px 10px 25px 6px #8a8a8a;
    transition: all 0.3s ease-in-out;
}

.movie-card:hover {
    box-shadow: 0px 15px 25px 9px #8a8a8a;
    width: 230px;
    height: 330px;
    cursor: pointer;
}

.movie-img{
    background-image: url('../assets/doct.jpg');
    width: 100%;
    height: 65%;
    background-size: cover;
    background-position: center;
    border-width: 1px;
    border-style: solid;
    border-color: #4b5d6b;
    color: #4f5b66 ;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-between;
}

.heart{
    width: 24px;
    align-items: flex-end;
    align-self: flex-end;
    padding: 8px;
}

.heart:hover{
    color: red;
    cursor: pointer;
}

.date{
    margin-bottom: 4px;
    color: white;
    font-size: 15px; 
}


.infos{
    flex: 1;
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    align-items: center;
    background-color: white;
    color: #4b5d6b;
}

.genero{
    font-size: 18px;
    align-self: center;
    color: #879199;
}

.bottom-container {
    width: 100%;
    height: 35%;
    border-width: 1px;
    border-style: solid;
    border-color: #c3d0d9;
    border-top: none;
    border-bottom: none;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}


.details {
    display: flex;
    flex-direction: row;
    
}

.stars{
    display: flex;
    flex-direction: row;
    width: 30px;
    justify-content: space-evenly;
    margin-right: 15px;
    font-size: 18px;
}

.price{
    margin-top: 10px;
    color: #4b5d6b;
    font-size: 16px;
}

.button{
    width: 101.7%;
    height:13%;
    background-color: #6658f5;
    color: white;
    border: none;
    border-radius: 4px;
    transition-duration: 0.4s;
    font-size: 18px;
}
.button:hover{
    background-color: #900703;
    cursor: pointer;
}

@media (max-width: 500px) {
  .all{

 }


 }


 @media (max-width: 600px) {
  .all{

 }
 }


 @media (max-width: 750px){
     .all{
         
         }
 }

</style>