<template>
  <div class="page-container">
    <!-- Header  -->
    <div class="content">
      <page-header></page-header>
      <h1>Let's build the app</h1>
      <!-- Content -->
      <!-- Stories -->
      <!-- Posts -->
      <post-container />
      <!-- Personal -->
      <!-- Profile -->
      <!-- Friend suggestion -->
    </div>
  </div>
</template>

<script>
import PageHeader from "../components/Header";
import PostContainer from "../components/Post";

export default {
  components: {
    PageHeader,
    PostContainer,
  },
};
</script>

<style lang="scss" scoped>
.page-container {
  margin: 0;
  min-height: 100vh;
  display: flex;
  background-color: #f1f2f5;

  .content {
    display: block;
  }
}
</style>
