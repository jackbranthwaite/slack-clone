<template>
  <div class="footer-container">
    <nuxt-link to="#" class="logo-container">
      <img src="~/static/slack.svg" alt="slack logo" class="logo" />
    </nuxt-link>
    <div class="footer-section">
      <div class="section-header">WHY SLACK?</div>
      <div class="section-links">
        <nuxt-link to="#" class="section-header-link"
          >Slack vs. Email</nuxt-link
        >
        <nuxt-link to="#" class="section-header-link">Channels</nuxt-link>
        <nuxt-link to="#" class="section-header-link">Engagement</nuxt-link>
        <nuxt-link to="#" class="section-header-link">Scale</nuxt-link>
        <nuxt-link to="#" class="section-header-link">Watch the Demo</nuxt-link>
      </div>
    </div>
    <div class="footer-section">
      <div class="section-header">PRODUCT</div>
      <div class="section-links">
        <nuxt-link to="#" class="section-header-link">Features</nuxt-link>
        <nuxt-link to="#" class="section-header-link">Intergrations</nuxt-link>
        <nuxt-link to="#" class="section-header-link">Enterprise</nuxt-link>
        <nuxt-link to="#" class="section-header-link">Solutions</nuxt-link>
      </div>
    </div>
    <div class="footer-section">
      <div class="section-header">PRICING</div>
      <div class="section-links">
        <nuxt-link to="#" class="section-header-link">Plans</nuxt-link>
        <nuxt-link to="#" class="section-header-link">Paid vs. Free</nuxt-link>
      </div>
    </div>
    <div class="footer-section">
      <div class="section-header">RESOURCES</div>
      <div class="section-links">
        <nuxt-link to="#" class="section-header-link">Partners</nuxt-link>
        <nuxt-link to="#" class="section-header-link">Developers</nuxt-link>
        <nuxt-link to="#" class="section-header-link">Community</nuxt-link>
        <nuxt-link to="#" class="section-header-link">Apps</nuxt-link>
        <nuxt-link to="#" class="section-header-link">Blog</nuxt-link>
        <nuxt-link to="#" class="section-header-link">Help Center</nuxt-link>
        <nuxt-link to="#" class="section-header-link">Events</nuxt-link>
      </div>
    </div>
    <div class="footer-section">
      <div class="section-header">Company</div>
      <div class="section-links">
        <nuxt-link to="#" class="section-header-link">About Us</nuxt-link>
        <nuxt-link to="#" class="section-header-link">Leadership</nuxt-link>
        <nuxt-link to="#" class="section-header-link"
          >Investor Relations</nuxt-link
        >
        <nuxt-link to="#" class="section-header-link">News</nuxt-link>
        <nuxt-link to="#" class="section-header-link">Media Kit</nuxt-link>
        <nuxt-link to="#" class="section-header-link">Careers</nuxt-link>
      </div>
    </div>
  </div>
</template>
<script>
import { defineComponent } from '@vue/composition-api'

export default defineComponent({
  setup() {}
})
</script>

<style lang="scss" scoped>
.footer-container {
  display: flex;
  justify-content: space-between;
  margin-left: auto;
  margin-right: auto;
  position: relative;
  width: 90%;
}
.logo {
  height: 100px;
  left: 0;
  position: absolute;
  top: 0;
  width: 100px;
}
.section-header {
  color: #000;
  font-size: 0.875rem;
  font-weight: 800;
}
.section-links {
  display: flex;
  flex-direction: column;
}
.section-header-link {
  color: #454245;
  font-size: 0.875rem;
  font-weight: 500;
  padding-top: 20px;
  text-decoration: none;
}
.section-header-link:hover {
  color: #1264a3;
}
</style>
