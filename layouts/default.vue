<template>
<v-app>
  <v-app-bar
  elevation="0"
  flat
  color=#003087

  height="28px"
  >
  
  <v-app-bar-title elevation="0" color="white" class="text-h6">紺</v-app-bar-title>

  </v-app-bar>





    <nuxt/>

  
  


</v-app>
</template>

<script>

  export default {
    data: () => ({
      items: [
        ['mdi-email', 'Inbox'],
        ['mdi-account-supervisor-circle', 'Supervisors'],
        ['mdi-clock-start', 'Clock-in'],
      ],
    }),
  }

</script>


