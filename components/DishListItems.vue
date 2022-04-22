<template>

    <div class="m-12">
        <img :src="item.image" alt="dish image" class="h-64 w-64 object-cover " >
        <strong><h3>{{item.title}}</h3></strong>
        <p>{{item.description}}</p>
    </div>
</template>

<script>
    export default {
        props:['item'],
        data() {
            return {

            }
        }
    }
</script>