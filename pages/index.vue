<template>
  <div class="pb-16">

        <h1 id="Head1" class="grid place-content-center">
          Welcome to my food blog 
        </h1>

        <h2 id="Head2">
          Nothing brings people together like good food
        </h2>

        <div class="flex flex-col md:flex-row justify-center gap-16 mt-8">
          <img class="w-46 md:w-86 lg:w-1/4" src="/pictures/dishImage.jpg">
          <img class="w-46 md:w-86 lg:w-1/4" src="/pictures/BrownieImage.jpg"/>
        </div>

        <div id="Text3">
          6 suprising facts you probably didn't know about mango!
        </div>

          <div class="flex flex-col md:flex-row justify-center gap-16 mt-16">
            <img class="w-46 md:w-86 lg:w-1/3" src="/pictures/MangoImage.jpg">
              <div>
                <ul id="Fact1" style="list-style-type:disc;">
                  <li>Mangos are real fibre bombs. Fibre is important for good bowel movements and healthy digestion. <br> By eating 150 grams of mango, you can get 12% of your recommended daily amount of fibre</li> <br>
                  <li>Carrots are known to be good for your eyes, but mangos contain superpowers as well. <br> Mangos contain substantial amounts of beat carotene, which is converted into vitamin A in your body. <br> Vitamin A is essential for your eye health and can prevent night blindess and dry eyes.</li> <br>
                  <li>The amounts of beta carotene in mangos not only contribute to healthy eyes, but are also important for your skin. In addition, mangos <br> also contain vitamin C, which is necessary for the production of collagen. Collagen is a protein that keeps your skin firm and elastic.</li> <br>
                  <li>Give your taste buds a smile and boost your immune system. The amount of vitamin C in mangos can boost your immune system. <br> Vitamin C has been shown to reduce the intensity and duration of the flu.</li> <br>
                  <li>Did you know that eating mango makes you happy? (And not only because you get such shiny hair). <br> This delicious fruit contains tryptophan, which converts your body into the “happiness hormone” serotonin. <br> Is your serotonin level too low? Then you can experience insomnia, depression and even anxiety.</li> <br>
                  <li>Mangos contain a certain substance called glutamic acid. Glutamic acid is said to strengthen memory and allow us to concentrate better. </li>
                </ul>
            </div>
         </div>
             
  </div>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>

<style>

#Head1{
  font-family: "Playfair-Display";
  font-size:xx-large;
  padding-top: 15px;
}

#Head2{
  font-family: "Playfair-Display";
  font-size: large;
  margin-top: 2ch;
  padding: 1.5ch;
  background-color: cornsilk;
  border-radius: 1ch;
  width: 25vw;
  height: fit-content;
  margin-left: auto;
  margin-right: auto;
  display:flex;
  justify-content: center;
  align-items: center;
}

#Text3{
  font-family: "Playfair-Display";
  font-size: large;
  margin-top: 3ch;
  padding: 1.5ch;
  background-color: cornsilk;
  border-radius: 1ch;
  width: 30vw;
  height: fit-content;
  margin-left: auto;
  margin-right: auto;
  display:flex;
  justify-content: center;
  align-items: center;
}

#Fact1{
  font-family: "Playfair-Display";
}

#Social1{
  font-family: "Playfair-Display";
  font-size: x-large;
  margin-top: 12ch;
  padding: 6ch;
  background-color: cornsilk;
  border-radius: 1ch;
  width: 100vw;
  height: fit-content;
  margin-left: auto;
  margin-right: auto;
  display:flex;
  justify-content: center;
  align-items: center;

}

</style>