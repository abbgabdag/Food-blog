<template>
<div>
  <h1 id="Title1" class="flex justify-center">These are some sweet and savory recipes you must try!</h1>
    
    <div class="flex justify-center mt-20">
      <div class="flex flex-wrap justify-center grid grid-cols-4 ">
        <div @click="goToDish(dish.id)" class="w-80 m-4" v-for="dish in dishes" :key="dish.id">
          <DishListItems :item="dish"></DishListItems>
        </div>
      </div>
    </div>
  </div>
</template>

<script>

import DishListItems from "../components/DishListItems.vue"

export default {
  name: 'IndexPage',
  async asyncData({$content}) {
    let dishes = await $content('dishes').sortBy('id', 'asc').without(['body']).fetch()
    return {
      dishes
    }
  },
  methods: {
    goToDish(id) {
      this.$router.push('/dish-details/'+id)
    },
    components: {
        DishListItems
    }
  }
}
</script>

<style>

#Title1{
  font-family: "Playfair-Display";
  font-size:xx-large;
  margin-top: 2ch;
  padding: 1.5ch;
  background-color: cornsilk;
  border-radius: 1ch;
  width: 45vw;
  height: fit-content;
  margin-left: auto;
  margin-right: auto;
  display:flex;
  justify-content: center;
  align-items: center;

}


</style>
