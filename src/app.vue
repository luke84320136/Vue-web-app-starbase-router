<template >
  <div id ="app">
    <h3>Starbase Router</h3>
    <h4>
      <router-link class="link" to="/data/people">來看看角色吧！</router-link> |
      <router-link class="link" to="/data/planets">探索星球吧！</router-link>
    </h4>
    <router-view></router-view>
  </div>
</template>
