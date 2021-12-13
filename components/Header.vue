<template>
  <div class="div-header">
    <h3 class="h3-head">
      popular post
    </h3>
    <img src="/photo-1.png" alt="" width="200px">
    <img src="/photo-2.png" alt="" width="200px">
    <img src="/photo-3.png" alt="" width="200px">
  </div>
</template>

<script>
export default {

}
</script>

<style>
.div-header{
  display: flex;
  flex-direction: column;
  float: left;
  padding: 30px 30px 34px 30px;
  border-right: 1px solid black;
  background-color: tomato;
}
.h3-head{
    text-align: center;
    padding-bottom: 15px;
}
img{
  padding: 10px;
}
</style>