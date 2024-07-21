<script>
export default {
 setup(){
  
 }
  data() {
    return {
      msg: 'Welcome to Your Vue.js App',
      status: 'pending'
      link: 'https://github.com/gks77/icp'
      task:[Task One, Task Two, Task Three]
    };
  },
};
</script>
<template>
  <h1>{{msg}}</h1>
  <h1 v-if="status === 'active'">Hello</h1>
  <h1 v-else-if="status === 'pending'">Bye</h1>
  <h1 v-else>Hi</h1>
</template>

