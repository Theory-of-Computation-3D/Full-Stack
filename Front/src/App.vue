<script setup lang="ts">

</script>

<template>
  <body>
    <header>
      <nav>
        <ul>
          
          <div class="name">
            <RouterLink to="/" class="headtxt">WAT DAI</RouterLink>
            
          </div>
          
          <div class="space"></div>
          <li><RouterLink to="/NakhonSiThammarat" class="menu">นครศรีธรรมราช</RouterLink></li>
          <li><RouterLink to="/NakhonSawan" class="menu">นครสวรรค์</RouterLink></li>
          <li><RouterLink to="/Nonthaburi" class="menu">นนทบุรี</RouterLink></li>
          <li><RouterLink to="/Narathiwat" class="menu">นราธิวาส</RouterLink></li>
          <li><RouterLink to="/UthaiThani" class="menu">อุทัยธานี</RouterLink></li>
          <div class="space"></div>
          <li><a href="#members" class="menu con">ทีมงาน</a></li>
          
        </ul>
      </nav>
    </header>
  </body>
  <RouterView></RouterView>
</template>



<style scoped>

* {
  
  margin: 0;
  padding: 0;
  /* font-family: ; */
  /* left: 0%; */
  box-sizing: border-box;
}

body{
  margin:0;
  background-color: transparent;
}

header {
  width: 100%;
  height: 72px;
  background-color: #03204C;
  /* background-color: transparent; */
  display: flex;
  justify-content: space-between;
  /* align-items: center; */
  position: relative;
  top: 0;
  margin: 0%;
  /* box-shadow: 1px 1px 10px; */
}

nav {
  width: 100%;
  height:100%;
  outline:white solid 1px;
}

ul {
  display: flex;  
  justify-content: space-between;
}

.headtxt{
  color:black;
  background-color:#ffffff;
  font-size: min(5vw, 1.2em);
}
.space {
  height: fit-content;
  background-color: #ffffff00;
  width: 15%;
}
.menu {
  list-style: none;
  display: inline-block;
  padding: 18px;
  background-color: #00000000;
  color: #ffffff;
  height: fit-content;
  width:fit-content;
  margin-left: 0px;
}
ul li
{
    list-style-type: none;
}

a {
  text-decoration: none;
}

nav > ul {
  display: flex;
  /* justify-content: space-evenly; */
  flex-wrap: wrap;
  align-items: center;
  padding-inline-start: 0;
  margin-block: 0;
  height: 100%;}
nav > ul {
  display: flex;
  /* justify-content: space-evenly; */
  flex-wrap: wrap;
  align-items: center;
  padding-inline-start: 0;
  margin-block: 0;
  height: 100%;
}

li > a {
  color: #dfdfe2;
  text-decoration: none;
}

nav > ul > li {
  color: #dfdfe2;
  display: block;
}

nav > ul > li:hover {
  background-color: #dfdfe22d;
  height: fit-content;
  width: fit-content;
  border-radius: 15px;
  cursor: pointer;
  transition: 0.2s;
}

nav > ul > li:hover a{
  color: #ffffff;
  cursor: pointer;
} 

.name { 
  /* justify-content: center; */
  text-align: center;
  height: fit-content;
  width: 160px;
  color: #000000;
  background-color: #FFFFFF; 
  font-size: min(5vw, 1.2em);
  border-radius: 10px;
  margin-left: 15px;
}

main{
  /* padding-top: 50px; */
  background-color: #035C96;
  width: 100%;
  position: static;
  left: 0%;
}

RouterLink{
  text-decoration: none;
  text-underline-offset: none;
}

</style>
