<template>
  <div class="hello">
    <div @click="txt">这是组件hello</div>
  </div>
</template>

<script>
export default {
  data () {
    return {
      msg: "Welcome to Your Vue.js App"
    };
  },
  methods: {
    txt () {
      console.log("ss");
    }
  }
};
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
