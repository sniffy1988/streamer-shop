<template>
  <div id="app">
    <div class="ui two item menu">
      <router-link to="/" class="item" active-class="active" exact="true">Home</router-link>
      <router-link to="/shop" class="item" active-class="active">Shop</router-link>
    </div>
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/shop">Shop</router-link>
    </div>
    <router-view/>
  </div>
</template>

<style>
</style>
