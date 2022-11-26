<template>
    
    <section class="dates">
        <div class="dates--intro">
            <p>Esperamos pueda encontrar lo que busca para su negocio o uso personal</p>
            <button>Acceder</button>
        </div>

        <div class="description">
            <p>Accede para agregar nuevos productos.</p>
        </div>
        <App :product:="newProduct"/>
        
    </section>
</template>

<style>
.dates{
    width: 45%;
    margin: auto;
}
.dates--intro{
    width: 100%;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
}
.dates--intro p{
    width: 90%;
    padding:  0px 8px;
    text-align: center;
    margin-bottom: 10px;
    font-weight: 900;
    font-size: 25px;
    margin: 2% auto;
}
.dates--intro button{
    padding: 3px 10px;
    background-color: green;
    color: white;
    border-radius: 20px;
    border: none;
    margin-top: 10px;
}
.dates--intro button:hover{
    padding: 3px 10px;
    background-color: white;
    color: green;
    border-radius: 20px;
    outline: 2px solid green;
}
.description p{
    padding: 20px;
    color: green;
    font-style: italic;
    font-weight: 800;
    font-size: 20px;

}
</style>
<script>
import App from '../App.vue'

export default {
    data() {
        return {

            newProduct: "Los productos nuevos que llegaron son las fundas para Xiaomi "

        }
    }
  
}
</script>
