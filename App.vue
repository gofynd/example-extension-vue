<template>
  <div id="app">
    <router-view />
  </div>
</template>

<script>
export default {
  name: 'App',
}
</script>

<style>
html {
  height: 100%;
  width: 100%;
  font-size: 8px;
}

body {
  margin: 0;
  font-family: 'Inter', sans-serif;
  background-color: #f8f8f8 !important;
  width: 100%;
  height: 100%;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

.flex-column {
  display: flex;
  flex-direction: column;
}

.flex-row {
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: space-between;
  gap: 10px;
}

.mr-r-12 {
  margin-right: 12px;
}

.cl-RoyalBlue {
  color: #2e31be;
  margin-left: 2px;
}
</style>
