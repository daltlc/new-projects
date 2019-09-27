<template>
  <div class="container hello">
    <h1>{{ msg }}</h1>
    <ul class="row">
      <li>
        <router-link to="/projects">Projects</router-link>
      </li>
      <li>
        <a href="https://github.com/daltlc">Github</a>
      </li>
      <li>
        <a href="https://linkedin.com/in/daltonlcarr">LinkedIn</a>
      </li>
    </ul>
    
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

<style lang="scss" scoped>
@import "@/styles/main.scss";

.hello{
  
  h1{
    font-size:8.2em;
    color:white;
    text-align: left;
  }
  ul{
   margin:0px;
   padding:0px;
    li{
    padding: 0px 20px;
    font-size:1.2em;
    a{
      color:white;
      &:hover{
        color:rgb(255, 207, 193);
        text-decoration: none!important;
      }
    }
  
    }
  }
}
</style>
