<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
.welcome{
  max-width: 400px;
  margin-top: 100px;
}
.welcome h2 {
  font-size: 3em;
}

.welcome button{
  margin: 30px auto;
}
</style>
