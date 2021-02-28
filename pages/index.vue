<template>
  <!-- bloques,elementos, modificares -->
  <!-- bloques componentes de nuestro sitio que queremos reutizar en otra parte -->
  <!-- elementos forman parte del bloque y no significan nada por si solos -->
  <!-- podemos usar bloques dentro de bloques -->
	<div class="container">
		<div class="card">   <!-- bloque -->
      <a href="" class="card__thumbnail"> <!-- elemento de la card -->
         <img class="card__img" src="@/assets/img/1.jpg" alt="">
      </a>
      <div class="card__text">
          <h3 class="card__title">Lorem ipsum dolor, sit amet consectetur </h3>
          <a href="#" class="card__link">Lorem ipsum dolor, sit amet consectetur </a>
          <p class="card__content">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quod, excepturi! Sed maxime accusantium harum hic aliquid dolorum nostrum quasi asperiores quas officiis illo impedit blanditiis dolores vel, corrupti pariatur dicta.</p>
          
          <a href="" role="button" class="button button--absolute"> <!-- nuevo bloque bloque  y modificador -->
            <span>Ver Más</span> 
            <i class="button_icon fas fa-arrow-right"></i>
          </a>
      </div>
    </div>
    <div class="frase"> 
      <h2 class="frase__texto">lorem ipsum dolor lorem</h2>
      <a href="" class="button" role="button">
        <span>Comprar</span>
        <i class="button_icon fas fa-shopping-cart"></i>
      </a>
    </div>
	<script src="https://kit.fontawesome.com/2c36e9b7b1.js" crossorigin="anonymous"></script>
	</div>
</template>

<script>
export default {}
</script>

<style>

</style>
