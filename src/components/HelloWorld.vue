<template>
<div class="content">
  <h1>{{ msg }}</h1>
  <span>{{ number }}</span>
</div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String,
    number: Number
  },

}
</script>


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
