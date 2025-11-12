<template>
  <div class="galeria">
    <h2>Galeria de Fotos</h2>
    <div class="fotos">
      <img src="../assets/DSCF1016.jpg" alt="Foto 1" />
      <img src="../assets/IMG_2391.jpg" alt="Foto 2" />
      <img src="../assets/IMG_2434.jpg" alt="Foto 3" />
    </div>
  </div>
</template>

<style>
.galeria {
  text-align: center;
  padding: 20px;
}
.fotos {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 15px;
}
.fotos img {
  width: 250px;
  border-radius: 10px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.2);
}
</style>
