<template>
  <div class="box">
    <div class="content">222</div>
    <div class="myInput">
      <input type="text">
      <div class="myButton"><button>发送</button></div>
    </div>
  </div>
</template>

<script></script>

<style scoped>
.box {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100%;
  width: 100%;
  flex-direction: column;
  background-color: rgb(245, 240, 240);
  padding: 20px;
  border-radius: 20px;


  .content {
    width: 1200px;
    height: 900px;
    border-radius: 20px;
  }

  .myInput {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 1200px;
    height: 40px;
    border-radius: 8px;
    border: 1px solid gray;
    margin: 50px;
    

    input {
      border: none; 
      outline: none;
      width: 95%;
      background-color: rgb(245, 240, 240);
      padding: 10px;
    }
  }

  .myButton {
    height:30px;
    width: 50px;
    width: 5%;
  }
}
</style>
