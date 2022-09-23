<template>

<Navbar/>

  <card url="https://www.lavanguardia.com/files/og_thumbnail/files/fp/uploads/2021/03/30/6063031b90a87.r_d.1083-871-0.jpeg" nombre="PIZZA" precio= "$ 150" descripcion="Las Mas deliciosas del Mundo"/>
  <card url="https://images.hola.com/imagenes/cocina/noticiaslibros/20210528190401/dia-internacional-hamburguesa-recetas-2021/0-957-454/dia-hamburguesa-m.jpg" nombre="Hamburgesa" precio= "$ 75" descripcion="Incluye papas y refresco"/>
  <card url="https://www.vvsupremo.com/wp-content/uploads/2016/02/900X570_Mexican-Style-Hot-Dogs.jpg" nombre="Hot Dog" precio= "$ 30" descripcion="Delicioso para uno solo"/>
  <card url="https://cdn2.cocinadelirante.com/sites/default/files/styles/gallerie/public/images/2018/08/receta-banderilla.jpg" nombre="Banderillas" precio= "$ 25" descripcion="Acompañadas con ingredientes de calidad"/>
  <card url="https://cdn2.cocinadelirante.com/sites/default/files/styles/gallerie/public/images/2018/08/receta-banderilla.jpg" nombre="SUSHI" precio= "$ 90" descripcion="Un pala exiquisito "/>
  <card url="https://www.recetas360.com/wp-content/uploads/2019/07/como-hacer-papas-fritas-de-mcdonals-500x500.jpg" nombre="Papas a la Francesa" precio= "$ 30 Orden" descripcion="Un pequeño Apetitivo"/>
<br>

<br>
<br>
  <Footer/>

</template>


<style>

</style>

<script>


  import Card from "./components/Card.vue";
  import Navbar from "./components/Navbar.vue";
  import Footer from "./components/Footer.vue"


  export default{
    components: { Card, Navbar, Footer}
  }
</script>

