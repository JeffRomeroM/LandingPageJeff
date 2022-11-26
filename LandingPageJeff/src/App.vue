<template>
  
  <Header/>
  
  <main>
    <Titles :nameCompany="title"/>
    <Informations :general="description"/>
    <Dates/>
    <Products />
  </main>
</template>

<script>
import Header from './components/Header.vue'
import Titles from './components/Titles.vue'
import Informations from './components/Informations.vue'
import Dates from './components/Dates.vue'
import Products from './components/Products.vue'


export default {

  components: { Header, Titles, Informations, Dates, Comment, Products },
  data() {
    return {
      title: "Jeffrin Tecnologies",

      description: "Somos una empresa consultora sobre productos tecnologicos, nuestro objetivo es mostrar tu opinion a los usuarios de la web."
    }
  },
  props: {
    product: {
      type: String,
      required: true
    }
  }
  
}

</script>
<style>
*{
  margin: 0;
  padding: 0;
  font-family: cursive;
}
main{
  width: 100%;
  display: flex;
  flex-wrap: wrap;
}
h6{
  color: black;
  border: 2px solid red;
  width: 100%;
  height: 20px;
}
</style>



