<template>
  <b-row
    align-h="center"
    class="mt-2"
  >
    <b-col>
      <b-button
        size="lg"
        variant="secondary"
        :block="true"
        :to="{ name: 'dataIndex' }"
      >
        Data Index
      </b-button>
    </b-col>
  </b-row>
</template>

<script>
export default {
  name: 'DataIndex',
}
</script>
