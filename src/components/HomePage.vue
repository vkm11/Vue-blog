<template>
  <!-- click event start1 -->
    <!-- <div>
        <h1>Hello from Home component</h1>
        // <h2>{{ data }}</h2>
        // <h2>{{ msg }}</h2> 
        <button v-on:click="hello('hello call')">Call Hello Function</button> 
        <button v-on:mouseover="hello('hello call')">Call Hello Function</button>
    </div> -->
  <!-- click event end1 -->

  <!-- Conditional Rendring start2 -->
  <div>
    <h2 v-if="show">Conditional Rendering in vue js</h2>
    <h2 v-else>Conditional Rendering else block</h2>
    <button v-on:click="display">Toggle Element</button>
  </div>
  <!-- Conditional Rendring End2 -->
</template>
<script>
export default {
  name: "Home-page",
  props: {
    data: String,
    msg: String,
  },
  //  Click event Start1

  //   methods:{ //method property
  //       hello(data){
  //         //   console.log("hello console called");
  //         //   alert("hello console called");
  //         alert(data)
  //       }
  //   }

  // Click event End1

  // Conditional Rendring start2
  data() {
    return { show: true };
  },
  methods: {
    display() {
      // this.show=false //only hide
      this.show = !this.show; // hide and show
    },
  },
 // Conditional Rendring End2

};
</script>
