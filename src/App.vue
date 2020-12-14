<template>
  <div id="app">
    <StringInterpolation name="vasavi"/>
   <life/>
    <events/>
    <raw/>
    <compute/>
    <obj/>
    <list/>
   
    <parent/>
   
  </div>
</template>

<script>
import Events from './components/Events.vue'
import Life from './components/Life.vue'
import Raw from './components/Raw.vue'
import Compute from './components/Compute.vue'
import StringInterpolation from './components/StringInterpolation.vue'
import List from './components/List.vue'
import Obj from './components/Obj.vue'

import Parent from './components/Parent.vue'



export default {
  name: 'App',
  components: {
   StringInterpolation,
    Events,
    Life,
    Raw,
    Compute,
    Obj,
    List,
   
    Parent,
    
    
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
