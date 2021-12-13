<template>
  <div>
    <Nav />
    <Header />
    <Mainjs />
    <Footerjs/>
  </div>
</template>

<script>
import { Nav } from "~/components/Nav.vue";
import { Header } from "~/components/Header.vue";
import { Mainjs } from "~/components/Mainjs.vue";
import { Footerjs } from "~/components/Footerjs.vue";
export default {
  // components: {
  //   Navbarheader,
  //   Header,
  //   Mainheader,
  //   Footerheader,
  // },
};
</script>

<style>
*{
 margin:0;
 padding: 0; 
}
  </style>
