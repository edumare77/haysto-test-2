<template>
  <div class="bg-primary h-screen p-2 relative md:pt-10 md:pb-0">
    <div class="flex flex-col mx-auto container-main">
      <span class="font-hand mb-2 block">Our Calculators</span>
      <div class="flex flex-col h-screen w-full md:flex-row">
        <TextCalculator></TextCalculator>
        <MortgageCalculator></MortgageCalculator>
      </div>
    </div>
  </div>
 
</template>

<script>
import TextCalculator from './TextCalculator.vue'
import MortgageCalculator from './MortgageCalculator.vue'

export default {
  name: 'welcome',
  components: {
    TextCalculator,
    MortgageCalculator
  }
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
