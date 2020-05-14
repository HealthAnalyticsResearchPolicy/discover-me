<template>
  <b-row
    align-h="center"
    class="mt-3"
  >
    <b-col>
      <b-row
        align-h="center"
        class="search p-4"
      >
        <b-col cols="10">
          <label for="search" class="search-label h1">I'm looking for: </label>
          <input type="text" id="search" class="search-text h2 mx-3">
          <span class="h1">.</span>
        </b-col>
      </b-row>
    </b-col>
  </b-row>
</template>

<script>
export default {
  name: 'SearchInput'
}
</script>

<style scoped>
.search {
	background-color: #FFB14B;
}
.search .search-text {
	border: 0;
	border-bottom: 2px solid black;
	text-align: center;
	background-color: inherit;
	max-width: 60%;
}
.search .search-text:hover,
.search .search-text:focus {
	background-color: #fe9000;
}
</style>
