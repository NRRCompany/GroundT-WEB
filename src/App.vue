<template>
  <app-header/>
  <app-side-navigation/>
  <app-contents/>
  <app-footer/>
</template>

<style scoped>
</style>
<script>
import AppHeader from "@/layouts/Header";
import AppContents from "@/layouts/Contents";
import AppFooter from "@/layouts/Footer";
import AppSideNavigation from "@/layouts/SideNavigation";
export default {
  components: { AppSideNavigation, AppHeader, AppFooter, AppContents }
}
</script>