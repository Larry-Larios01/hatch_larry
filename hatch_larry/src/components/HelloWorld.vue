<script lang="ts">


import { defineComponent} from "vue";


export default defineComponent({
    name: "HatchEmulation"
    
})

</script>


<template>
  <div class="main">

    <div class="header">

      <div class="egg_container">
        <button class="egg">egg</button>
        Hatch
        <select name="version" id="selversion">
            <option value="opt1">1.0</option>
            <option value="opt1">1.1</option>
        </select>
      
      </div>



      <div class="links">
        <a href="#">Home</a>
        <a href="#">configuration</a>
        <a href="#">CLI</a>
        <a href="#">Plugins</a>
        <a href="#">How-to</a>
        <a href="#">Tutorials</a>
        <a href="#">Meta</a>
        <a href="#">Blogs</a>


      </div>



    </div>












  </div>
</template>

<style scoped>
.main{
  height: 100vh;
  width: 100vw;
  display: grid;
  grid-template-rows: 100px 1fr 70px;
  grid-template-columns: 270px 1fr 270px  ;
  
}

.header{
  margin: 0;
  padding: 0;
  display: grid;
  grid-column-start: 2;
  background-color: #4051B5;
  grid-template-rows: 1fr 1fr;


}

.links {
display: flex;
align-items: flex-end;
justify-content: flex-start;
font-size: 15px;
margin: 20px;
grid-row-start: 2;
}


.links a{
  margin: 0 10px;
  color: white;
}

.egg_container{
  display: flex;
  grid-row-start: 1;
  margin: 20px;
  height: 10px;

}

.egg{
  height: 30px;
  width: 30px;
  margin-left: 10px;
}




</style>


