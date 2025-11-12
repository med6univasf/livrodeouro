<template>
  <section class="galeria">
    
    <div class="fotos">
        <img src="../assets/A1.jpg" alt="Foto 1" />
      <img src="../assets/A2.jpg" alt="Foto 2" />
      <img src="../assets/A3.jpg" alt="Foto 3" />
      <!-- adicione mais fotos se quiser -->
    </div>
  </section>
</template>

<style>
.galeria {
  padding: 20px;
  background-color: #f8f8f8;
}

.galeria h2 {
  color: #004d40;
  margin-bottom: 15px;
}

.fotos {
  display: flex;
  gap: 15px;
  overflow-x: auto;
  scroll-behavior: smooth;
}

.fotos img {
  height: 220px;
  border-radius: 10px;
  flex-shrink: 0;
  box-shadow: 0 2px 6px rgba(0, 0, 0, 0.2);
}
</style>
