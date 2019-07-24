<template>
  <div>
    <Header></Header>
    <Todo></Todo>
    <Footer></Footer>
  </div>

</template>
<script>
import Header from '../components/Header.vue';
import Footer from '../components/Footer.vue';
import Todo from '../components/Todo.vue';

export default {
  name: 'day',
  components: {
    Header,
    Footer,
    Todo,
  },
};
</script>
