<template>
  <div id="app" class="w-full">
    <Header/>
    <Graph/>
    <Cards/>
    <Support/>
    <Route/>
    <Testimonies/>
    <Learn/>
    <Fader/>
    <Footer/>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Graph from './components/Graph.vue'
import Cards from './components/Cards.vue'
import Support from './components/Support.vue'
import Route from './components/Routes.vue'
import Testimonies from './components/Testimonies.vue'
import Learn from './components/Learn.vue'
import Fader from './components/Fader.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    Graph,
    Cards,
    Support,
    Route,
    Testimonies,
    Learn,
    Fader,
    Footer,
  }
}
</script>


