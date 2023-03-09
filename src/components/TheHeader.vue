
<template>
  <div class="header">
    <div class="emojis">
      <img src="https://cliply.co/wp-content/uploads/2020/02/392002770_ROCKET_EMOJI_400px.gif" alt="">
      <img src="https://cliply.co/wp-content/uploads/2020/08/442008112_GLANCING_AVATAR_3D_400px.gif" alt="">
      <img src="https://cliply.co/wp-content/uploads/2020/08/432008031_FOLDED_HANDS_3D_LIGHT_SKIN_TONE_400.png" alt="">
      <img src="https://cliply.co/wp-content/uploads/2020/10/392010140_GHOST_EMOJI_400px.gif" alt="">
    </div>
    <div class="name">
      <h1>Leonardo <span>"Frontend"</span> Castro</h1>
    </div>
    <div class="description">
      <p>Bachelor's degree in Software Engineering, living in Brazil and recording some moments of my life.</p>
    </div>
  </div>
</template>

<style scoped>
header{
  display: grid;
  align-items: center;
  justify-content: center;
}

.emojis img{
  width: 100px;
}

.name{
  padding: 4.5rem 0;
  width: 80%;
  background-image: 
    linear-gradient(to right, #f75c5c, #1a6bf6,#7526ff); 
  -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;  
  animation: rainbow-animation 300s linear infinite;
}

.name h1{
  font-size: 3.2rem;
  color: #1a6bf6;
}

.name span{
    color: #6e34d4;
}

.description{
  width: 45%;
}

.description p{
  font-weight: 400;
}



.text-rainbow-animation {
  font-family:arial black;
  font-size:70px;
  background-image: 
    linear-gradient(to right, #1a6bf6,#6e34d4,#76ff71 ); 
  -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;  
  animation: rainbow-animation 10000s linear infinite;
}

@keyframes rainbow-animation {
    to {
        background-position: 4500vh;
    }
}


</style>


