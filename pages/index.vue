<template>
  <div class="page-container">
    <!-- Header  -->
    <page-header></page-header>
    <!-- Content -->
      <!-- Stories -->
      <!-- Posts -->
      <!-- Personal -->
        <!-- Profile -->
        <!-- Friend suggestion -->
  </div>
</template>

<script>
import PageHeader from '../components/Header'
export default {
  components: {
    PageHeader
  },
}
</script>

<style>
.page-container {
  margin: 0;
  min-height: 100vh;
  display: flex;
  background-color: #f1f2f5;
}
</style>
