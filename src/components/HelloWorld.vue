<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      How easy is it to work with vue.js?
    </p>
    <h3>Useful links</h3>
    <ul>
      <li><a href="https://google.com" target="_blank" rel="noopener">Awesome link</a></li>
      <li><a href="/contact" target="_blank" rel="noopener">Another awesome link</a></li>
      <!-- <router-link to='/contact'>Contact</router-link> -->
    </ul>
    
  </div>

</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
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
