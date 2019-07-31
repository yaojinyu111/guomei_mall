<template>
  <div id="app">
    <!-- <download></download> -->
    <search></search>
  </div>
</template>

<script>
import download from './components/index/download/download'
import search from './components/index/search/search'

export default {
  name: 'app',
  components: {
    download,
    search
  }
}
</script>

<style>

</style>
