<template>
  <div class="article">
    <h1 class="title">{{ title }}</h1>
    <div class="text">{{ text }}</div>
    <div class="views">{{ views }}</div>
  </div>
</template>

<script>
export default {
  name: 'Article',
  props: {
    title: String,
    text: String,
    views: Number,
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.article {
  text-align: left;
}

.text {
  font-size: 20px;
  margin-bottom: 20px;
}

.views {
  font-size: 20px;
}
</style>
