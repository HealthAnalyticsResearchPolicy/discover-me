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
        v-b-toggle.data-index
      >
        Data Index
      </b-button>
      <b-collapse
        id="data-index"
        class="mt-2"
      >
        <b-row
          align-h="center"
        >
          <b-col>
            <p class="h3">Category</p>
            <ul>
              <li>Indicator</li>
              <li>Indicator</li>
              <li>Indicator</li>
              <li>Indicator</li>
              <li>Indicator</li>
              <li>Indicator</li>
            </ul>
          </b-col>
          <b-col>
            <p class="h3">Category</p>
            <ul>
              <li>Indicator</li>
              <li>Indicator</li>
              <li>Indicator</li>
              <li>Indicator</li>
              <li>Indicator</li>
              <li>Indicator</li>
            </ul>
          </b-col>
          <b-col>
            <p class="h3">Category</p>
            <ul>
              <li>Indicator</li>
              <li>Indicator</li>
              <li>Indicator</li>
              <li>Indicator</li>
              <li>Indicator</li>
              <li>Indicator</li>
            </ul>
          </b-col>
          <b-col>
            <p class="h3">Category</p>
            <ul>
              <li>Indicator</li>
              <li>Indicator</li>
              <li>Indicator</li>
              <li>Indicator</li>
              <li>Indicator</li>
              <li>Indicator</li>
            </ul>
          </b-col>
        </b-row>
      </b-collapse>
    </b-col>
  </b-row>
</template>

<script>
export default {
  name: 'DataIndex',
}
</script>
