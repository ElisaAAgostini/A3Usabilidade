<template>
  <q-page class="flex fundomar">
    <div class="column">
  <div>SOS Baia </div>
  <div><q-input rounded standout v-model="text" label="Rounded outlined" /></div>
  <div><q-input rounded standout v-model="text" label="Rounded outlined" /></div>
</div>
    
    
    
  </q-page>
</template>

<script>
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'IndexPage'
})
</script>
<style>
.fundomar {
  background-size: cover;
  background-image: url(../assets/bela-praia-tropical-vazia-mar-oceano-com-nuvem-branca-no-fundo-do-ceu-azul_74190-13668.avif);
}
</style>
