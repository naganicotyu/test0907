<template>
<v-app>
 
  <v-app-bar
  elevation="0"
  color="black"
  max-height="20px"
  >
  
  <v-app-bar-title
  elevation="0"
  color="gray"
  
  >
    <p>titte</p>
  </v-app-bar-title>

  </v-app-bar>



<v-container>
  
  
  <v-main>
  <v-container>

    <nuxt/>

  </v-container>
  </v-main>
  
  <v-navigation-drawer
  elevation="0"
  permanent
  expand-on-hover
  
  fixed
  height="100vh"
  >
    <v-list>
    <v-list-item
    v-for="([icon,text],i) in items"
    :key="i"
    link
    >
      <v-list-item-icon>
      <v-icon>{{ icon }}</v-icon>
      </v-list-item-icon>

      <v-list-item-content>
      <v-list-item-title>{{ text }}</v-list-item-title>
      </v-list-item-content>

</v-list-item>
</v-list>
</v-navigation-drawer>

</v-container>

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
