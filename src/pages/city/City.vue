<template>
  <div>
    <city-header></city-header>
    <city-Search></city-Search>
  </div>
</template>

<script>
import cityHeader from './components/header'
import citySearch from './components/search'

export default {
  name: 'city',
  components: {
    cityHeader,
    citySearch
  }
}
</script>

<style lang="stylus" scoped>
</style>
