<script setup>
import { RouterLink, RouterView } from 'vue-router'
import TheHeader from './components/TheHeader.vue'
</script>

<template>
  <div class="body">
    <div class="container">
      <TheHeader />
    </div>
    <div class="secondary">
      <nav>
        <RouterLink to="/"><span>📜</span>About</RouterLink>
        <RouterLink to="/linkedin"><span>💼</span> Linkedin</RouterLink>
        <RouterLink to="/github"><span>💾</span> Github</RouterLink>
        <RouterLink to="/about"><span>😎</span> Instagram</RouterLink>
        <RouterLink to="/"><span>📸</span> Facebook</RouterLink>
        <RouterLink to="/about"><span>💡</span> Experiences</RouterLink>
      </nav>
      <div class="info">
        <RouterView />
      </div>
    </div>
    

  </div>

</template>

<style scoped>

.body{
  display: flex;
}
.container{
  display: flex;
  height: 100vh;
  width: 50vw;
  background-color: #ffffff;
  justify-content: center;
  align-items: center;
  
}

.secondary{
  box-shadow: 120px 0px 200px 5px #a496bd;
  height: 100vh;
  width: 50vw;
  background-color: rgb(255, 255, 255);
  
}

.secondary nav{
  display: grid;
  grid-template-columns: auto auto auto;
  

}

nav a{
  font-size: 1.8rem;
  padding: 3rem 5rem;
  text-decoration: none;
  font-weight: bold;
  color: #000000;
}

nav a span{
  margin-right: 5px;
  border-radius: 100%;
  padding: 8px;
  background-color: #f1f8f8;
}

.info{
  margin-top: 100px;
  display: flex;
  justify-content: center;
  align-items: center;
}

</style>

