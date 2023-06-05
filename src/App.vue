<script setup>
import listagemlivros from '@/componentes/listagemlivro.vue';

import meucarrinho from '@/componentes/meucarrinho.vue';

</script>

<template>
  <h1>Minha livraria</h1>
  <div class="container-geral">
   
    <listagemlivros/>

    <meucarrinho/>
  </div>
</template>

<style scoped>

.container-geral {
  /* display: flex;
  justify-content: space-between; */
  display: grid;
  grid-template-columns: 3fr 1fr;
}

.carrinho {
  /* min-width: 20%; */
}


.card-livro {
  margin: 5px 10px;
  padding: 10px;
  background-color: beige;
  border-radius: 10px;
  width: 180px;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}


</style>
