<template>
  <div id="app">
    <NavigationBar></NavigationBar>
    <b-container>
      <SearchInput></SearchInput>
      <DataIndex></DataIndex>
      <router-view></router-view>
    </b-container>
  </div>
</template>

<script>
import NavigationBar from './components/NavigationBar.vue'
import SearchInput from './components/SearchInput.vue'
import DataIndex from './components/DataIndex'

export default {
  name: 'App',
  components: {
    NavigationBar,
    SearchInput,
    DataIndex,
  },
}
</script>
