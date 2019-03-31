<template>
  <div id="app">
   
    <router-view/>
    <amount></amount>
    <hr>
    <counter></counter>
  </div>
</template>

<script>
import amount from  "./components/amount.vue"
import counter from "./components/counter.vue"
export default {
  name: 'App',
  data(){
    return{};

  },
   components: {
    counter,
    amount
  }
}
</script>

<style>

</style>
