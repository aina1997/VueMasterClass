<template>
  <div class="container">
    <h1>Aquesta és la pàgina principal</h1>
    <div class="row">
      <ButtonCustom 
      ></ButtonCustom>
    </div>
    <div class="row">
      <div class="col-md-4"></div>
      <div class="col-md-4"><h1 class="mt-5 p-3"></h1></div>
      <div class="col-md-4"></div>
    </div>
  </div>
</template>



<script>

import ButtonCustom from './Button.vue';
export default {
  name: 'PaginaPrincipal',
  components: {
    ButtonCustom
  },
  data(){
    return{
      buttonList: 
        [
          
        ]
    }
  },
  methods: {
  }
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
