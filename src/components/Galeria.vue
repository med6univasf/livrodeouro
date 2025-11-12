<template>
  <section>
    <h2>Galeria</h2>
    <div class="galeria">
      <div class="foto" v-for="n in 3" :key="n">Espaço para foto {{ n }}</div>
    </div>
  </section>
</template>

<style scoped>
.galeria {
  display: flex;
  overflow-x: auto;
  gap: 16px;
  padding: 20px;
}

.foto {
  min-width: 300px;
  height: 200px;
  background-color: #e0e0e0;
  border: 2px solid gold;
  border-radius: 12px;
  display: flex;
  align-items: center;
  justify-content: center;
  color: #004d40;
  font-weight: bold;
}
</style>
