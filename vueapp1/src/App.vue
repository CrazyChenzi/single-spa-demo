<template>
  <span id="vueapp1">
    <p>App1 is working!</p>
    <p>comment me on and off to see HMR</p>
    <router-link to="/vueapp2/about">go to vueapp2 about</router-link>
    <router-view></router-view>
  </span>
</template>

<style>
#vueapp1 {
  display: flex;
  flex-direction: column;
  align-items: center;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
