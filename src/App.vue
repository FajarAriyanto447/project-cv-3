<template>
  <div id="app">
    <div class="cv">
      <list-cv-1/>
    </div>
    <div class="cv-satu">
      <list-cv-2/>
    </div>
  </div>
</template>

<script>



import ListCv1 from './components/ListCv1.vue'
import ListCv2 from './components/ListCv2.vue'
export default {
  name: 'App',
  components: {
   ListCv1,
   ListCv2
  }
}
</script>

<style>
body{
    font-family: 'Courier New', Courier, monospace;
    text-align: left;

}
.op {
  background-color: rgb(230, 228, 228);
  border-radius: 1px;
  position: relative;
  width: 300px;
  border: 2px;
  padding: 20px;
}

.pp {
  background-color: whitesmoke;
  border-radius: 1px;
  position: relative;
  width: 700px;
  border: 2px;
  padding: 20px;
}

img {
  width: 250px;
}
p,
ul,
li {
  font-size: 15px;
}

hr{
  border-top: 2px dotted black;
}
</style>