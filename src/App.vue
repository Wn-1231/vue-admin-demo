<!--
 * @Author: wn
 * @Date: 2021-01-18 00:08:58
 * @LastEditTime: 2021-06-17 13:52:20
 * @LastEditors: wn
 * @Description: 
-->
<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <HelloWorld msg="Hello Vue 3.0 + Vite" />
  <div>
    {{ a }}
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
  },
  setup() {
    return {
      a: 1,
    };
  },
};
</script>
