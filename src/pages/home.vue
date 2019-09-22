<template>
  <div>
    <my-header></my-header>
    <my-content></my-content>
    <my-navigation></my-navigation>
  </div>
</template>
<script>
import myHeader from "./components/myHeader.vue";
import myContent from "./components/myContent.vue";
import myNavigation from "./components/myNavigation.vue";
export default {
  components: {
    myHeader,
    myContent,
    myNavigation
  }
};
</script>
