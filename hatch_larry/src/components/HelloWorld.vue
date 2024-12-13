<script lang="ts">


import { defineComponent} from "vue";


export default defineComponent({
    name: "HatchEmulation"
    
})

</script>


<template>
  <div class="main">
    <div class="empty-container1"></div>
    <div class="empty-container2"></div>


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
        <a href="#">Blog</a>

      </div>
      

     


    </div>

    <div class="body">

      <div class="sidebar-left">
        <p>Home</p>
        <a href="#">about</a>
        <p>WalkThrough</p>
        <a href="#">Installation</a>
        <a href="#">Introduction</a>
        <a href="#">Enviroments</a>
        <a href="#">Versioning</a>
        <a href="#">Builds</a>
        <p>Learn</p>
        <a href="#">Next Steps</a>
        <a href="#">Why Hatch?</a>
        <p>History</p>
        <a href="#">Hatch</a>
        <a href="#">Hatching</a>
        <p>Community</p>
        <a href="#">Users</a>
        <a href="#">Highlights</a>
        <a href="#">Contributing</a>


      </div>

      <div class="sidebar-right">
        <p>Table of Contents</p>
        <a href="#">License</a>
        <a href="#">Navigation</a>




      </div>

      <div class="main-content">

          <div class="first-part">
            <h2 id="hatch-main">Hatch</h2>
            <button id="btn-edit-page">edit this page</button>

          </div>

          <div class="first-grid-of-main-content">
            <img src="./icons/snakehatch.svg" alt="snakesvg" id="imagesnake">
            <table class="status-table">
              <thead>
                <tr>
                  <th>Section</th>
                  <th>Details</th>
                </tr>
              </thead>
              <tbody>
                <tr>
                  <th>CI/CD</th>
                  <td>
                    <span class="badge green">test passing</span>
                    <span class="badge red">build hatch failing</span>
                    <span class="badge red">build hatchling failing</span>
                  </td>
                </tr>
                <tr>
                  <th>Docs</th>
                  <td>
                    <span class="badge green">release docs passing</span>
                    <span class="badge green">dev docs passing</span>
                  </td>
                </tr>
                <tr>
                  <th>Package</th>
                  <td>
                    <span class="badge blue">PyPI v1.13.0</span>
                    <span class="badge blue">Python 3.8 | 3.9 | 3.10 | 3.11 | 3.12 | 3.13</span>
                    <span class="badge blue">Installs 39M/month</span>
                    <span class="badge blue">Downloads 364k</span>
                  </td>
                </tr>
                <tr>
                  <th>Meta</th>
                  <td>
                    <span class="badge purple">Hatch</span>
                    <span class="badge purple">Ruff</span>
                    <span class="badge purple">types Mypy</span>
                    <span class="badge pink">license MIT</span>
                    <span class="badge pink">Sponsors ❤️ 10</span>
                  </td>
                </tr>
              </tbody>
           </table>
                            

            


          </div>

          <p>Hatch is a modern, extensible Python project manager. See the <a href="#">Why Hatch? </a>page for more information.</p>




          
          
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
  grid-row-start: 1;
  background-color: #4051B5;
  grid-template-rows: 40px 70px;
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
.empty-container1{
  grid-row-start: 1;
  background-color:#4051B5;
}
.empty-container2{
  grid-row-start: 1;
  grid-column-start: 3;
  background-color:#4051B5;
}


.body{
  display: grid;
  grid-template-columns: 245px 690px 123px;
  grid-column-start: 2;
  grid-row-start: 2;
}

.sidebar-left{
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  grid-column-start: 1;
  margin: 24px;
}

.sidebar-left a{
  text-decoration: none;
  margin: 0 10px;
  color: black;
}

.sidebar-left p{
  margin: 0 10px;
  color: grey;
}

.sidebar-right{
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  grid-column-start: 3;
  margin: 24px;
}

.sidebar-right a{
  text-decoration: none;
  margin: 0 10px;
  color: black;
}

.sidebar-right p{
  margin: 0 10px;
  color: grey;
}

.main-content{
  grid-column-start: 2;
  grid-row-start: 1;
}
.first-part{
  display: flex; /* Contenedor flexible */
  justify-content: space-between; /* Separa el título y el botón */
  align-items: center; /* Centra verticalmente los elementos */
  padding: 10px 20px;

}

.first-grid-of-main-content{
  display: grid;
  grid-template-columns: 350px 350px;
  grid-template-rows: 500px;
}

#imagesnake{
  grid-column-start: 1;
  grid-column-end: 1;
  grid-row-start: 1;
  height: 437px;
  width: 270px;
}
.status-table {
  width: 100%;
  border-collapse: collapse;
  font-family: Arial, sans-serif;
  margin: 20px 0;
  grid-row-start: 1;
  grid-column-start: 2;
  grid-column-end: 2;
  grid-row-start:1;
}
.status-table th,
.status-table td {
  border: 1px solid #ddd;
  padding: 10px;
  text-align: left;
}

.status-table th {
  background-color: #f4f4f4;
  font-weight: bold;
  width: 69px;
}

.badge {
  display: inline-block;
  padding: 5px 10px;
  margin: 2px 0;
  border-radius: 5px;
  color: white;
  font-size: 12px;
}

.green {
  background-color: #28a745;
}

.red {
  background-color: #dc3545;
}

.blue {
  background-color: #007bff;
}

.purple {
  background-color: #6f42c1;
}

.pink {
  background-color: #e83e8c;
}




</style>


