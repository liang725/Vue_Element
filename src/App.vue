<template>
  <div id="app">
    <!-- <h1 id="htitle">{{ message }}</h1>
    <TestButton /> -->
    <!-- <user-view></user-view> -->
    <router-view></router-view>
  </div>
</template>

<script>
//import TestButton from './views/element/TestButton.vue';
//import UserView from './views/element/UserView.vue';
// import UserView from './views/element/QuestionView.vue';

export default {
  // components: {
  //   //TestButton,
  //   //UserView,
  // },
  data() {
    return {
      message: "hello vue",
    };
  },
};
</script>

<style>
#htitle {
  color: rgb(143, 46, 46);
}
</style>