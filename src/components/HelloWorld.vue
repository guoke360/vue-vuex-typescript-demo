<template>
  <div class="hello">
    <h2>NGL DEMO</h2>
       <img src="/src/assets/dar.jpg">
       <br>
    <router-link to="/vuedemo">某练习测试的自我跳转页面</router-link>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  mounted () {
    this.hello()
    const a = '11'
  },
  methods: {
    hello () {
      console.log('Hello world')
    }
  }
})
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
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
