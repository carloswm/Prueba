<template>
  <button @click="this.$emit('accion')">{{texto}}</button>
</template>

<script>
export default {
  name: 'AccionSaldo',
  props: {
    texto: String
  }
}
</script>

<style>

</style>