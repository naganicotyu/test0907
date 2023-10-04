
<template>

<v-carousel>
<v-carousel-item
v-for="(image,i) in images"
    :key="i"
    :src="image.src"
    reverse-transition="fade-transition"
      transition="fade-transition"
>
</v-carousel-item>
</v-carousel>

</template>



<script>

export default {
    data () {
      return {
        images: [
          {
            src: 'https://cdn.vuetifyjs.com/images/carousel/squirrel.jpg'
          },
          {
            src: '/static/top-img2.jpg'
          },
          {
            src: 'https://cdn.vuetifyjs.com/images/carousel/squirrel.jpg'
          }
        ]
      }
    }
  }

</script>

<style>

</style>