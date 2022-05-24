<template>
  <div>
    <h1>Hello from Home component</h1>
    <!-- <h2>{{ data }}</h2>
    <h2>{{ msg }}</h2> -->
    <!-- <button v-on:click="hello('hello call')">Call Hello Function</button> -->
    <button v-on:mouseover="hello('hello call')">Call Hello Function</button>
  </div>
</template>
<script>
export default {
  name: "Home-page",
  props: {
    data: String,
    msg: String
  },methods:{
      hello(data){
        //   console.log("hello console called");
        //   alert("hello console called");
        alert(data)
      }
  }
};
</script>
