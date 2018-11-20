<template>
  <div id="app">
    <div class="ui two item menu">
      <router-link to="/" class="item" active-class="active" exact>Home</router-link>
      <router-link to="/shop" class="item" active-class="active">Shop</router-link>
    </div>
    <router-view/>
  </div>
</template>

<style>
</style>
