<script lang="ts">


import { defineComponent} from "vue";


export default defineComponent({
    name: "HatchEmulation"
    
})

</script>


<template>
  <div class="main">

    <div class="header">

      <div class="nav_bar">
        <button class="egg">egg</button>
        <p Class="HatchWord">Hatch</p>
        <select name="version" id="selversion">
            <option value="opt1">1.0</option>
            <option value="opt1">1.1</option>
        </select>
      
      </div>


      <div class="nav_bar_header_2">
        <button class="sun_btn">sun</button>
        <input type="text" class="search-input" placeholder="🔎 Buscar">
        <a href="#">pypa/Hatch</a>



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
  grid-template-columns: 698px 621px;


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
  text-decoration: none;
  margin: 0 10px;
  color: white;
}

.nav_bar{
  display: flex;
  align-items: center;
  gap: 10px;
  grid-row-start: 1;
  color: white;
  margin: 20px;
  height: 10px;
}


.egg{
  display: inline-block;
  margin: 10px;
  height: 30px;
  width: 30px;
  margin-left: 10px;
  background-color: #4051B5;
  border: #4051B5;
  color: white;
}

#selversion{
display: inline-block;
margin:10px;
height: 30px;
width: 60px;
background-color: #4051B5;
border: #4051B5;
color: white;
}
.HatchWord{
  display: inline-block;
  margin: 10px;
  
}

.nav_bar_header_2{
  display: flex;
  align-items: center;
  gap: 10px;
  grid-row-start: 1;
  grid-column-start: 2;
  color: white;
  margin: 20px;
  height: 10px;

}
.nav_bar_header_2 a{
  text-decoration: none;
  margin: 0 10px;
  color: white;
}

.sun_btn{
  display: inline-block;
  margin: 10px;
  height: 30px;
  width: 30px;
  margin-left: 10px;
  background-color: #4051B5;
  border: #4051B5;
  color: white;
}

.search-input{
  background-color: #5766BE;
  color: white;
  border: 0;
}



</style>


