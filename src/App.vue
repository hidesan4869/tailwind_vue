<template>
    <div id="app">
        <HeaderItem />
        <IndexTop />
    </div>
</template>

<script>
import HeaderItem from './components/HeaderItem.vue'
import IndexTop from './components/pages/IndexTop.vue'


export default {
  name: 'App',
  components: {
      HeaderItem,
      IndexTop
  }
}
</script>

<style>

</style>
