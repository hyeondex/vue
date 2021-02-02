<template>
  <div id="app">
    <todoHeader></todoHeader>
    <todoInput></todoInput>
    <todoList></todoList>
    <todoFooter></todoFooter>
  </div>
</template>

<script>
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
#app{
  margin: 0;
  padding: 0;
  outline: 1px solid red;
  font-size:1em;
}
button{
  outline: none;
  border: none;
  background:transparent;
  font-size:1em;
}
ul, li{
  list-style: none;
  padding: 0;
  margin:0;
}
button:hover{
  color:#fff;
  transition:all ease 0.3s ;
}
</style>
