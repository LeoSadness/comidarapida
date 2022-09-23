<template>
<body>

<h1>COMIDA RAPIDA</h1>
<h2>ALONDRA HERNANDEZ REYES 10 "A" DGS </h2> 

<div class="navbar">
  <a class="active" href="#"><i class="fa fa-fw fa-home"></i> PROMOCIONES</a> 
  <a href="#"><i class="fa fa-fw fa-search"></i>MENU</a> 
  <a href="#"><i class="fa fa-fw fa-envelope"></i>GALERIA DE FOTOS</a> 
  <a href="#"><i class="fa fa-fw fa-user"></i>VER MIS PEDIDOS</a>
</div>
</body>

</template>


<style>
body {font-family: Arial, Helvetica, sans-serif;}

.navbar {
  width: 100%;
  background-color: #FF5733;
  overflow: auto;
}

.navbar a {
  float: left;
  padding: 12px;
  color: white;
  text-decoration: none;
  font-size: 17px;
}

.navbar a:hover {
  background-color: #000;
}

.active {
  background-color: #FF5733;
}

@media screen and (max-width: 500px) {
  .navbar a {
    float: none;
    display: block;
  }
}
</style>

<script>    
</script>