<script setup>
import ContentApi from "../components/ContentApi.vue";
</script>


<template>
   <div class="container-fluid">
    <div class="col-12 text-center">
      <p>Sua review online rapida</p>
      <h1>Metaview</h1>
      <p>Criado por Paulo José e Eron Tiago</p>
      <h5>Usando:</h5>
      <p><img src="@/assets/vuejs-ar21.png"></p>
    </div>
  </div>
  <div class="container">

      <ContentApi></ContentApi>
      <ContentApi></ContentApi>
      <ContentApi></ContentApi>
      <ContentApi></ContentApi>
  </div>
</template>

<style scoped>
.container-fluid {
  margin-bottom: 75px;
}
.col-12 {
  margin-top: 50px;
}
.col-12 h1 {
  font-size: 50px;
}
img {
  height: 300px;

}
.container {
  display: flex;
  flex-wrap: wrap;
  align-content: center; 
  justify-content: center; 
}
</style>

