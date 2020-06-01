<template>
  <div class="flex h-screen" id="app">
    <div class="m-auto">
      <div class="flex justify-between">
        <router-link class="mr-4" to="/">Go to Home</router-link>
        <router-link to="/about">Go to About</router-link>
      </div>

      <router-view></router-view>
    </div>
  </div>
</template>

<style>
#app {
  background: #fff;
}
</style>
