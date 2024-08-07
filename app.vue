<template>
  <NuxtLayout>
  <v-layout class="rounded rounded-md">
    <v-app-bar title="Application bar"></v-app-bar>
    
    <v-navigation-drawer>
      <v-list>
        <v-list-item title="Home" to="/" />
        <v-list-item title="Test" to="/test" />
      </v-list>
    </v-navigation-drawer>
    
    <v-main class="d-flex align-center justify-center" style="min-height: 300px;">
      <NuxtRouteAnnouncer />
      <NuxtPage />
    </v-main>
  </v-layout>
</NuxtLayout>
</template>