<template>
  <div class="nav">
    <ul class="ul-nav">
    <a href=""><li class="li-nav">Github</li></a>
    <a href=""><li class="li-nav">Facebook</li></a>
    <a href=""><li class="li-nav">Youtube</li></a>
    </ul>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.ul-nav{
  display: flex;
  padding: 15px 20px;
  border-bottom: 1px solid black;
  background-color: lightblue;
  position: sticky;
}
.li-nav{
  list-style: none;
  margin-left: 25px;
}
a{
  text-decoration: none;
}
</style>