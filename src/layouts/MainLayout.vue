<template>
  <div class="nav-background-img">
  </div>
  <q-layout view="hHh lpR fFf">

    <q-page-container>
      <q-page class="row justify-center item-center">
        <router-view />
      </q-page>
    </q-page-container>

  </q-layout>
</template>
<style>
.nav-background-img {
  background-image: url('../assets/Portrait_dot_040823_background.jpg');
  background-size: cover;
  width: 100%;
  height: 100vh;
  position: fixed;
  background-repeat: no-repeat;
  background-position: 0 0;
}
</style>