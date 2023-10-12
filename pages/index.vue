<template>
<v-container>
<v-row>
<v-col><home-introduction /></v-col>
<v-col><home-body /></v-col>
</v-row>
<HomeCard />
</v-container>
</template>




<script>
  export default {
    name: 'IndexPage'
  }
</script>

<style>
html {
  height:100%;
  background: linear-gradient(#05FBFF, #1E00FF);
}
</style>