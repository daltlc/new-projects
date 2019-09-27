<template>
  <div class="home">
    <HelloWorld msg="Dalton Carr" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "home",
  components: {
    HelloWorld
  }
};
</script>

<style lang="scss" scoped>
.home{
  
  height: 98vh;
  display: flex;
  align-items:center;
  background-image:url('https://picsum.photos/id/184/4288/2848');
  background-size:cover;
  
}
</style>
