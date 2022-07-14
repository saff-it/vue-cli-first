<template>
  <div>

    <div class="container">

        <div class="jumbo-txt">
            <span>Verso i confini dell'Universo!</span>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Maiores ullam non quasi consectetur sint necessitatibus culpa commodi! Ratione explicabo amet illum, totam fuga fugit provident.</p>
            <button>Scopri di più</button>
     </div>
        

    </div>

  </div>
</template>

<script>
export default {

}
</script>

<style>
.container{
    width: 100%;
    height: 650px;
    background-image: url(https://static.geopop.it/wp-content/uploads/sites/32/2022/07/james-webb-prime-immagini.jpeg);
    background-size: cover;
}

div.jumbo-txt{
    width: 40%;
    padding: 100px;
    text-align: left;

}

div.jumbo-txt span{
    color: white;
    font-size: 6rem;
    
}

div.jumbo-txt p{
    color: white;
    width: 80%;  
    background-color: rgba(0, 0, 0, 0.418);
    padding: 10px;
    border-radius: 5px;
    
}

button{
    background-color: #1D5DA4;
    border: none;
}

</style>