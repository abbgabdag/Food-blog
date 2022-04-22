<template>
    <div class="w-1/3 mx-auto">
        <img class="mt-12" :src="dish.image" />
        <h1 class="text-3xl mb-8 mt-8">{{dish.title}}</h1>
        <p class="mb-8">{{dish.description}}</p>
        <nuxt-content :document="dish"></nuxt-content>
    </div>
</template>

<script>
 export default {
    async asyncData({$content, params}) {
        
        let dish = await $content('dishes/dish'+params.id).fetch()
        console.log(dish)

        return {
            dish
        }
    },
}
</script>