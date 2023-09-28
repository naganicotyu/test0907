
<template>

<v-carousel
dark="true"
>
<v-carousel-item>
    v-for="(image,i) in image"
    :key="i"
    :src="image.src"

</v-carousel-item>
</v-carousel>
</template>



<script>

export default {
    data () {
      return {
        image: [
          {
            src: '/static/top-img1.jpg'
          },
          {
            src: '/static/top-img2.jpg'
          },
          {
            src: '/static/top-img3.jpg'
          }
        ]
      }
    }
  }

</script>

<style>

</style>