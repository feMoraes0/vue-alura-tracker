<template>
  <div class="box has-text-height-bold">
    <div class="columns">
      <div class="column is-7">
        Descrição da tarefa 2
      </div>
      <div class="column">
        <Cronometro :tempoEmSegundos="15" />
      </div>
    </div>
  </div>
</template>

<script>
import { defineComponent } from 'vue';
import Cronometro from './Cronometro.vue';

export default defineComponent({
  name: 'Tarefa',
  components: {
    Cronometro,
  }
})
</script>

<style scoped>
.box {
  background-color: #faf0ca;
}
</style>
