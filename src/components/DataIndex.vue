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
        v-b-modal="'data-index-modal'"
      >
        Data Index
      </b-button>
      <b-modal
        id="data-index-modal"
        size="lg"
        title="Data Index"
        :hide-footer="true"
      >
        body goes here
      </b-modal>
    </b-col>
  </b-row>
</template>

<script>
export default {
  name: 'DataIndex',
}
</script>
