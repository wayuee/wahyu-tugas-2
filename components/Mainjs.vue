<template>
  <div class="mainjs">
    <h3 class="h3-main">Title Heading</h3>
    <p class="p-main">Title descrition</p>
    <img class="img-main" src="/photo-4.png" alt="" width="450px">
    <p class="p-main">Some text...</p>
    <p class="p-main">Lorem ipsum dolor sit amet consectetur adipisicing elit. Doloribus commodi dolorem blanditiis voluptatum non? Dolor vero non minima nam expedita.</p>
    <p class="p-main"> some oldered list:</p>
    <ul class="ul-main">
      <a href=""><li class="li-main">Photo-1</li></a>
      <a href=""><li class="li-main">Photo-2</li></a>
      <a href=""><li class="li-main">Photo-3</li></a>
      <a href=""><li class="li-main">Photo-4</li></a>
    </ul>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.h3-main{
  padding: 5px;
  
}
.img-main{
  margin-left:6%;

}
.p-main{
  margin-bottom: 10px;
  margin-left:23%;
}
.ul-main{
  padding: 5px;
  margin-left:25%;
}
.li-main{
  list-style: decimal;
  margin-bottom: 4.5px;
}
.h3-main{
  margin-left:23%;
  margin-bottom: 5px;
}
.mainjs{
  background-color: rgb(253, 253, 173);
}
</style>