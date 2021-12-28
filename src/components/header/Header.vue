<template>
  <div class="header-container">
    <div class="left-side">
      <nuxt-link to="#" class="logo-container">
        <img src="~/static/slack_text.svg" alt="slack logo" class="logo" />
      </nuxt-link>
      <div class="left-menu">
        <nuxt-link class="menu-link" to="#">Product</nuxt-link>
        <nuxt-link class="menu-link" to="#">Enterprise</nuxt-link>
        <nuxt-link class="menu-link" to="#">Resources</nuxt-link>
        <nuxt-link class="menu-link" to="#">Pricing</nuxt-link>
      </div>
    </div>
    <div class="right-side">
      <div class="right-side-container">
        <nuxt-link class="sign-in" to="#">Sign in</nuxt-link>
        <styled-button button-text="TALK TO SALES" />
        <styled-button button-text="TRY FOR FREE" fill />
      </div>
    </div>
  </div>
</template>
<script>
import { defineComponent } from '@vue/composition-api'
import StyledButton from '../styled-button/StyledButton.vue'

export default defineComponent({
  components: { StyledButton },
  setup() {}
})
</script>

<style lang="scss" scoped>
@import '~assets/styles/config';
.header-container {
  align-items: center;
  display: flex;
  height: 50px;
  justify-content: space-between;
  margin-left: auto;
  margin-right: auto;
  margin-top: 30px;
  width: 90vw;
}
.left-side {
  align-items: center;
  display: flex;
  width: 50%;
}
.left-menu {
  display: flex;
  justify-content: space-between;
  padding-left: 20px;
  width: 100%;
}
.right-side {
  align-items: center;
  display: flex;
  justify-content: flex-end;
  width: 50%;
}
.right-side-container {
  align-items: center;
  display: flex;
  justify-content: space-between;
  width: 80%;
}
.sign-in {
  font-size: 16px;
  text-decoration: none;
}
.logo {
  height: auto;
  width: 150px;
}
.menu-link {
  text-decoration: none;
}
</style>
