<script setup lang="ts">
import CustomTitle from './CustomTitle.vue';
</script>
<template>
  <div class="p-2 flex justify-center flex-col">
    <p class="text-cyan">Estamos para ayudarte</p>
    <CustomTitle variant="h1" class="text-4xl mb-5 mt-3">
      ¿Tienes problemas para<br />
      <span class="under">entender el mercado </span><br />de la publicidad digital?
    </CustomTitle>
    <p class="mb-2">
      El Mercado de la publicidad online es incierto y complejo, Admetricks te
      <mark class="text-cyan bg-transparent">
        ayuda a visibilizar cómo desempeñan las campañas y contenidos</mark
      >
      versus los de tu competencia en tiempo real con reportes y alertas automáticas
    </p>
    <div class="flex flex-wrap justify-center items-center gap-4 mt-4">
      <RouterLink class="p-3 bg-cyan pl-10 pr-10 text-black rounded-full" to="/currency"
        >Ver datos del CLP</RouterLink
      >
      <a class="text-white">Ver funcionalidades</a>
    </div>
  </div>
</template>

<style scoped>
h1 {
  position: relative;
  z-index: 10;
}
.under {
  white-space: nowrap;
  font-weight: bold;
  position: relative;
}

.under::before {
  content: '';
  position: absolute;
  width: 100%;
  height: 40%;
  bottom: 0;
  border-radius: 200px;
  background: linear-gradient(111.3deg, #076585 9.6%, #5a8037 93.6%);
  z-index: -1;
}
</style>
