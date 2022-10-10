<template>
  <div class="app-container">
    <nav>
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </nav>
    <router-view />
  </div>
</template>

<style>
.app-container {
  background-color: #faf9fa;
  height: 100%;
  width: 100%;
}
</style>
