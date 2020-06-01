<template>
  <div class="m-auto">
    <h1 class="text-5xl text-center text-gray-800">{{ msg }}</h1>
    <p class="text-xl text-center">
      You can easily use this template to run a
      <br />
      <span class="bg-gray-300 rounded-sm p-1 text-teal-600">vue.js</span>
      frontend using tailwindcss framework
    </p>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
