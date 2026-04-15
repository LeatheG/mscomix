<template>
  <!--made on 5/1/25-->
  <div id="app">
    <Comp1 />

    <Comp2 />
    <Space />
    <Comp3 />
    <Space />
    <Comp4 />
    <Space />
    <Contact />
  </div>
</template>

<script>
import Comp1 from './components/Comp1.vue';
import Comp2 from './components/Comp2.vue';
import Comp3 from './components/Comp3.vue';
import Comp4 from './components/Comp4.vue';
import Contact from './components/Contact.vue';
import Space from './components/Space.vue';

export default {
  name: 'App',
  components: {
    Comp1,
    Comp2,
    Comp3,
    Comp4,
    Contact,
    Space,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 0px;
}
</style>
