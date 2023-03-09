<template>
    <div>
        <div class="container-linkedin">
            <img src="https://media.licdn.com/dms/image/D4D03AQGRKT0LFaF7Jg/profile-displayphoto-shrink_800_800/0/1675808009591?e=1683158400&v=beta&t=ljkAr4rSKie_rbpkqVIYmw9rpsxBOEdgNoLN3V_BEmQ" alt="">
            <div class="text-linkedin">
                <p> Me chamo Leonardo Silva Castro , tenho 21 anos, sou apaixonado por programação, café e jogos eletrônicos.</p> 
            </div>
        </div>
        
      </div>
</template>

<style scoped>

.container-linkedin{
    display: flex;
    box-shadow: 5px 1px 15px 1px #9c9c9c;
    border-radius: 0 10px 10px;
    max-width: 55rem;
}

.text-linkedin{
    padding: 20px;
    background-color: #fafafe;
    display: flex;
    justify-content: center;
    align-items: center;
    border-radius: 0 10px 10px 0;
}

.text-linkedin:hover{
    background: rgb(68,136,254);
background: linear-gradient(90deg, rgba(68,136,254,1) 0%, rgba(198,165,255,1) 100%);
color: #fff;
}

.text-linkedin p{
    font-weight: 400;
}

img{
    width: 15rem;
    border-radius: 10px 0 0 10px;

}

</style>