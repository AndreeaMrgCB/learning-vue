<template>
    <div class="header">
    <ul>
      <li><a href="https://google.com" target="_blank" rel="noopener">Awesome link</a></li>
      <li><a href="https://bing.com" target="_blank" rel="noopener">Another awesome link</a></li>
      <router-link to='/contact'>Contact</router-link>
    </ul>
    </div>
</template>

<script>
export default {
  name: 'Header'
}
</script>

<style>
.header {
    background-color: red;
    height: 100px;
    }

li {
    list-style: none;
}
</style>