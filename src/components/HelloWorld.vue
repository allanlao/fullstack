<template>
<div class="flex justify-center items-center h-screen">
 
    <h1 class="bg-gray-500 text-7xl text-white border-blue-200  w-1/2">{{ message }}</h1>
  
</div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },

  data(){
    return{
      message : 'hi there',
    }
  }
}
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
