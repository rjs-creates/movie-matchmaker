<template>
  <div class="app-bg">
    <h1>Movie Match Maker</h1>
    <router-view />
  </div>
</template>

<style scoped>
.app-bg {
  min-height: 100vh;
  background: #e0e0e0;
  width: 100vw;
  min-width: 100vw;
  position: fixed;
  top: 0;
  left: 0;
}

h1 {
  text-align: center;
  margin-bottom: 2rem;
  color: #333;
  font-size: 2.2rem;
  font-weight: 600;
}
</style>