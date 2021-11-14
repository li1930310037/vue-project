<template>
  <div id="app">
    <h1>我是Vue3</h1>
    <h2>姓名：{{name}}</h2>
    <h2>年龄：{{age}}</h2>
    <button @click="sayHello">点我一下</button>
  </div>
</template>

<script>
export default {
  name: 'app',
  setup() {
    let name = 'lisi'
    let age = 19
    function sayHello() {
      alert('你好')
    }
    return {
      name,
      age,
      sayHello
    }
  }
}
</script>

<style>

</style>
