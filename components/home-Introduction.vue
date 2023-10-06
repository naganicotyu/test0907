
<template>

<v-carousel
width="600px"
>
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
            src: '/image/top-img1.jpg'
          },
          {
            src: '/image/top-img3.jpg'
          },
          {
            src: '/image/top-img2.jpg'
          }
        ]
      }
    }
  }

</script>

<style>

</style>