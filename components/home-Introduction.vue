
<template>

<v-carousel
dark="true"
>
<v-carousel-item>
    v-for="(image,i) in items"
    :key="i"
    :src="image.src"

</v-carousel-item>
</v-carousel>
</template>



<script>

export default {
    data () {
      return {
        items: [
          {
            src: 'https://cdn.vuetifyjs.com/images/carousel/squirrel.jpg'
          },
          {
            src: 'https://cdn.vuetifyjs.com/images/carousel/sky.jpg'
          },
          {
            src: 'https://cdn.vuetifyjs.com/images/carousel/bird.jpg'
          },
          {
            src: 'https://cdn.vuetifyjs.com/images/carousel/planet.jpg'
          }
        ]
      }
    }
  }

</script>

<style>

</style>