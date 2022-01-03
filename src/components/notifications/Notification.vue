<template>
  <div class="notification-container">
    <p class="notification-text">
      Slack is your digital HQ. Meet the new features keeping teams connected in
      a work-from-anywhere world.
    </p>
    <nuxt-link to="#" class="lets-go-link">Let's go</nuxt-link>
  </div>
</template>

<script>
import { defineComponent } from '@vue/composition-api'

export default defineComponent({
  setup() {}
})
</script>

<style lang="scss" scoped>
.notification-container {
  align-items: center;
  background-color: #1264a3;
  border-radius: 50px;
  display: flex;
  height: 80px;
  margin-bottom: 20px;
  margin-left: auto;
  margin-right: auto;
  margin-top: 20px;
  padding-left: 50px;
  padding-right: 50px;
  width: 95%;
}
.notification-text {
  color: #fff;
}
.lets-go-link {
  color: #fff;
  font-weight: 700;
  padding-left: 5px;
}
</style>
