<template>
  <div>
    <button class="button">Получить ответ!</button>
  </div>
</template>

<script>
export default {
  name: 'Button',
  props: {
    text: String,
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.button {
    display: flex;
    justify-content: center;
    align-items: center;
    border-radius: 5px;
    background-color: #0000FF;
    color: #fff;
    font-size: 15px;
    margin-top: 30px;
    width: 150px;
    height: 40px;
}
</style>