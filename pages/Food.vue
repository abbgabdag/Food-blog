<template>
<div>
    <div id="Food1">
        Different food cultures
    </div>


    <div class="flex flex-wrap jusitfy-around justify-center justify-between mt-20 mr-20 ml-20">
        <Nuxt-link to="JapanF"><div id="Jpan1"> Japanese food culture</div><img style="width: 500px;" src="/pictures/JapanFlag.jpg"></Nuxt-link> 
        <Nuxt-link to="ItalianF"><div id="Ital1"> Italian food culture</div><img style="width: 500px;" src="/pictures/ItalianFlag.jpg"></Nuxt-link> 
    </div>

    <div class="flex flex-wrap jusitfy-around justify-center justify-between mt-20 mr-20 ml-20 pb-20">
        <Nuxt-link to="BelgiumF"><div id="Belg1"> Belgan food </div><img style="width: 500px;" src="/pictures/BelgianFlag.jpg"></Nuxt-link> 
        <Nuxt-link to="MexicanF"><div id="Mexi1"> Mexican food culture</div><img style="width: 500px;" src="/pictures/MexicoFlag.jpg"></Nuxt-link> 
    </div>

</div>
</template>

<style>
    @font-face {
        font-family: "Playfair-Display";
        src: local("Playfair-Display"), 
            url("~static/PlayfairDisplay-VariableFont_wght.ttf") format("truetype");
    }

#Food1{
  font-family: "Playfair-Display";
  font-size: x-large;
  margin-top: 2ch;
  padding: 1ch;
  background-color: cornsilk;
  border-radius: 1ch;
  width: 20vw;
  height: fit-content;
  margin-left: auto;
  margin-right: auto;
  display:flex;
  justify-content: center;
  align-items: center;
}

#Belg1{
  font-family: "Playfair-Display";
  font-size: x-large;
  margin-top: 2ch;
  padding: 1ch;
  background-color: cornsilk;
  border-radius: 1ch;
  width: 20vw;
  height: fit-content;
  margin-left: auto;
  margin-right: auto;
  display:flex;
  justify-content: center;
  align-items: center;
}

#Jpan1{
  font-family: "Playfair-Display";
  font-size: x-large;
  margin-top: 2ch;
  padding: 1ch;
  background-color: cornsilk;
  border-radius: 1ch;
  width: 20vw;
  height: fit-content;
  margin-left: auto;
  margin-right: auto;
  display:flex;
  justify-content: center;
  align-items: center;
}

#Mexi1{
  font-family: "Playfair-Display";
  font-size: x-large;
  margin-top: 2ch;
  padding: 1ch;
  background-color: cornsilk;
  border-radius: 1ch;
  width: 20vw;
  height: fit-content;
  margin-left: auto;
  margin-right: auto;
  display:flex;
  justify-content: center;
  align-items: center;
}

#Ital1{
  font-family: "Playfair-Display";
  font-size: x-large;
  margin-top: 2ch;
  padding: 1ch;
  background-color: cornsilk;
  border-radius: 1ch;
  width: 20vw;
  height: fit-content;
  margin-left: auto;
  margin-right: auto;
  display:flex;
  justify-content: center;
  align-items: center;
}

#Food1{
  font-family: "Playfair-Display";
  font-size: x-large;
  margin-top: 2ch;
  padding: 1ch;
  background-color: cornsilk;
  border-radius: 1ch;
  width: 20vw;
  height: fit-content;
  margin-left: auto;
  margin-right: auto;
  display:flex;
  justify-content: center;
  align-items: center;
}



</style>