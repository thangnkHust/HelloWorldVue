<template>
  <div id="app">
    <div v-show="isShow">
      <h2 :id="id">Hello world</h2>
    </div>
    <button @click="isShow = !isShow">An | Hien</button>
  </div>
</template>

<script>

export default {
  name: 'App',
  components: {
  },
  data() {
    return {
      isShow: true,
      id: "test"
    }
  }
}
</script>

<style>
#test{
  color: blue;
}
</style>
