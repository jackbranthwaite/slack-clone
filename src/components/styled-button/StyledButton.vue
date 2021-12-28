<template>
  <div
    class="button-container"
    :style="fill ? 'background-color: #611f69' : null"
  >
    <div class="button-text-container">
      <nuxt-link
        class="button-text"
        :style="fill ? 'color: #fff' : null"
        to="#"
        >{{ buttonText }}</nuxt-link
      >
    </div>
  </div>
</template>
<script>
import { defineComponent } from '@vue/composition-api'

export default defineComponent({
  props: {
    buttonText: {
      type: String,
      default: ''
    },
    fill: {
      type: Boolean,
      default: false
    },
    small: {
      type: Boolean,
      default: false
    },
    medium: {
      type: Boolean,
      default: false
    },
    large: {
      type: Boolean,
      default: false
    }
  },
  setup() {}
})
</script>
<style lang="scss" scoped>
.button-container {
  align-items: center;
  border-radius: 3px;
  display: flex;
  justify-content: center;
  outline: solid #611f69 1px;
  padding: 5px 10px;
}
.button-text {
  color: #611f69;
  text-decoration: none;
}
</style>
