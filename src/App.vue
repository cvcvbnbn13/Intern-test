<template>
  <div id="app">
    <Header></Header>
    <Main></Main>
    <Subscr></Subscr>
    <QaArea></QaArea>
  </div>
</template>

<script>
import Header from '@/views/Header.vue'
import Main from '@/views/Main.vue'
import Subscr from '@/views/Subscr.vue'
import QaArea from '@/views/QaArea.vue'
export default {
  name: 'App',
  components: {
    Header,
    Main,
    Subscr,
    QaArea
  }
}
</script>

<style>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 微軟正黑體, Helvetica, Arial, sans-serif;
}
#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  width: 100%;
  /* color: #2c3e50;
  margin-top: 60px; */
}
</style>
