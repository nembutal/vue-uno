<template >
  <div class="caja">
    <div class="cajaint">
      <a href="#">btn1</a>
      <a href="#">btn2</a>
      <a href="#">btn3</a>
      <a href="#">btn4</a>
    </div>
  </div>

</template>

<script>
  export default{

  }
</script>

<style media="screen">
  *{
    padding:0px;
    margin:0px;
    box-sizing: border-box;
  }
  .caja{
    width:100%;
    background:red;
    display:flex;
    justify-content: center;
    color:white;
    padding:100px;
  }
  .caja a{
    color:white;
    padding:10px;
    background:black;
    text-decoration: none;

  }
  .caja a:hover{
    background:gray;
  }
  .cajaint{
    width:80%;
    max-width:1400px;
    background:blue;
    display:flex;
    justify-content: center;
  }
  @media screen and (max-width:600px){
    .caja{
      background:blue;
      justify-content: center;
      padding:0px;
    }
  }
</style>
