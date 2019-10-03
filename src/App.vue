<template>
  <div >
    <div class="todo-container">
    <div class="todo-wrap">
      <todoHeader/>
      <todo-main/>
      <todoFooter/>
    </div>
  </div>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'
import Main from './components/Main.vue'


export default {
  components: {
    todoHeader:Header,
    todoFooter:Footer,
    todoMain:Main,
  }
}
</script>

<style scoped>


.todo-container {
  width: 600px;
  margin: 0 auto;
}
.todo-container .todo-wrap {
  padding: 10px;
  border: 1px solid #ddd;
  border-radius: 5px;
}

</style>
