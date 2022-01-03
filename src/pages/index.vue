<template>
  <div class="main-content">
    <notification />
  </div>
</template>
<script>
import { defineComponent } from '@vue/composition-api'
import Notification from '~/components/notifications/Notification.vue'

export default defineComponent({
  components: { Notification },
  setup() {}
})
</script>

