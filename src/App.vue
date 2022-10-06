<script setup>
  import HelloWorld from './components/HelloWorld.vue'
  import CityPostalCode from './components/CityPostalCode.vue'
</script>

<template>
  
  <div class="search">
    <CityPostalCode />
  </div>
  
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}

.search {
    background: linear-gradient(118.89deg, #2E6785 14.9%, #22536D 67.78%);
    box-shadow: 0px 7px 9px rgba(0, 0, 0, 0.1);
    border-radius: 12px;
    padding: 26px;
    gap: 12px;
}
</style>
