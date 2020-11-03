<template>
  <comp-a>
    <div>Comp B</div>
  </comp-a>
</template>

<script>
import CompA from './CompA.vue'

export default {
  name: 'CompB',
  components: {
    CompA
  }
}
</script>