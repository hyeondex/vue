<template>
  <div id="app">
    <todoHeader></todoHeader>
    <todoInput></todoInput>
    <todoList></todoList>
    <todoFooter></todoFooter>
  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import todoHeader from '@/components/todoHeader'
import todoInput from '@/components/todoInput'
import todoList from '@/components/todoList'
import todoFooter from '@/components/todoFooter'



export default {
  name: 'App',
  components: {
    todoHeader,
    todoInput,
    todoList,
    todoFooter
  }
}
</script>

<style>
#app div{
  outline: 1px solid red;
  font-size:1em;
}
</style>
