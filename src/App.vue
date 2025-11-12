<template>
  <div id="app" class="app">
    <header class="topo">
      <img src="./assets/Br.jpg" alt="Brasão da Turma" class="brasao" />
      <h1>Livro de Ouro</h1>
      <h2>Turma Matheus Rodrigues Lopes</h2>
      <h3>Medicina Turma VI - UNIVASF</h3>
      <p class="descricao">
        Este é o nosso Livro de Ouro digital! <br />
        Contribua com a nossa formatura e tenha seu nome eternizado em nossa página.
      </p>
    </header>

    <Galeria />
    <Rodape />
  </div>
</template>

<script>
import Galeria from "./components/Galeria.vue";
import Rodape from "./components/Rodape.vue";

export default {
  name: "App",
  components: {
    Galeria,
    Rodape,
  },
};
</script>

<style>
.app {
  text-align: center;
  font-family: "Helvetica", sans-serif;
  background-color: #ffffff;
  color: #004d40;
}

.topo {
  padding: 40px 10px;
}

.brasao {
  width: 160px;
  margin-bottom: 15px;
}

h1 {
  font-size: 2.2em;
  margin-bottom: 5px;
}

h2 {
  font-size: 1.5em;
  color: #00796b;
  margin-bottom: 3px;
}

h3 {
  font-size: 1.3em;
  color: #009688;
  margin-bottom: 15px;
}

.descricao {
  font-size: 1.1em;
  line-height: 1.5;
  color: #333;
}
</style>
