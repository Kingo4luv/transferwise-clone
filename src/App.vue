<template>
  <div id="app" class="w-full mb-20">
    <Header/>
    <Graph/>
    <Cards/>
    <Support/>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Graph from './components/Graph.vue'
import Cards from './components/Cards.vue'
import Support from './components/Support.vue'

export default {
  name: 'App',
  components: {
    Header,
    Graph,
    Cards,
    Support,
  }
}
</script>


