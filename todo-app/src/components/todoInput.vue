<template>
  <div>
    <div class="input">
      <input type="text" class="input-box" v-model="inputText" placeholder="할 일을 입력하세요.">
      <button type="button" @click="addTodo">add</button>
    </div>
    <div>
      inputText 테스트 : {{inputText}}
    </div>



  </div>

</template>

<script>
export default {
  name: "todoInput",
  data: function (){
    return{
      inputText : '',
    }
  },
  created() {
    if(localStorage.length > 0){

      localStorage.setItem("", "").getItem.key()
      console.log(localStorage.setItem("", ""));
    }
  },
  methods:{
    addTodo : function (){
    }
  }
}
</script>

<style scoped>
.input{
  border-bottom: 5px solid black;
  display: flex;
  justify-content: space-between;
  margin: 0 auto;
}
input{
  width: calc(100% - 60px);
  padding: 5px;
  box-sizing: border-box;
  font-size:1em;
  outline: none;
  border: none;

}
button{
  margin-left:10px;
  width: 50px;
  height: 50px;
  background:black;
  cursor: pointer;
}
</style>