<template>
  <code class="code"><slot /></code>
</template>
<script>
import { defineComponent } from '@vue/composition-api'

export default defineComponent({
  setup() {}
})
</script>

<style lang="scss" scoped>
.code {
  background-color: #f6efe8;
  font-family: Consolas, Menlo, Monaco, Lucida Console, Liberation Mono,
    DejaVu Sans Mono, Bitstream Vera Sans Mono, Courier New, monospace,
    sans-serif;
  font-size: 14px;
  padding: 1px 5px;
}
</style>
