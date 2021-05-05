<template>

  <div id="list">
    <h3 v-for="(todo, index) in todos" :key="index">{{ todo }}</h3>
  </div>

</template>

<script>

export default {
  name: 'TodoList',
  data() {
    return {
      todos: [
        'dental plan',
        'lisa needs braces',
        'home lawn',
        'refinancin',
        'i dont know'
      ]
    }
  }
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

h3 {
  margin: 20px 0 0;
}

</style>
