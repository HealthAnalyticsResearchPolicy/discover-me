<template>
  <div id="app">
    <NavigationBar></NavigationBar>
    <b-container>
      <SearchInput></SearchInput>
    </b-container>
  </div>
</template>

<script>
import NavigationBar from './components/NavigationBar.vue'
import SearchInput from './components/SearchInput.vue'

export default {
  name: 'App',
  components: {
    NavigationBar,
    SearchInput
  },
}
</script>
