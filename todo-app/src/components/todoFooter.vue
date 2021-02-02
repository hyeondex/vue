<template>
  <div>
    <button type="button" class="clearbtn">XXX</button>
  </div>
</template>

<script>
export default {
  name: "todoFooter"
}
</script>

<style scoped>
  button{
    display: block;
    width : 300px;
    height: auto;
    margin : 0 auto;
    background: black;
    text-align: center;
    cursor: pointer;
  }
  button:hover{
    color:#fff;
    transition:all ease 0.3s ;
  }
</style>