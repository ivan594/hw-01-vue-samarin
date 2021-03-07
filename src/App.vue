<template>
  <div id="app">
    <Article 
    title="Автостопом к ответу жизни, Вселенной и всего такого"
    text="10 октября 2020 года исполнилось 10 лет с первого «Дня 42», потому что 1010102 = 42. Сегодня делимся переводом поста об этом удивительном числе. Автор — профессор компьютерных наук Лилльского университета управления Жан Поль Делахайе, также написавший книгу «Formal methods in artificial intelligence», которая вышла еще в 1987 году. Он рассказывает о некоторых аллюзиях на 42, об этом числе в математических последовательностях и, конечно, о 42 в контексте задачи о сумме трех кубов. Подробности под катом."
    views="Количество просмотров статьи: 42"
    />
    <Button/>
  </div>
</template>

<script>
import Article from './components/Article.vue'
import Button from './components/Button.vue'

export default {
  name: 'App',
  components: {
    Article,
    Button
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
