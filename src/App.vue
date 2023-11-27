<template>
  <app-header/>
  <app-side-navigation/>
  <router-view/>
  <app-footer/>
</template>

<style scoped>
</style>
<script>
import AppHeader from "@/layouts/Header";
import AppFooter from "@/layouts/Footer";
import AppSideNavigation from "@/layouts/SideNavigation";
export default {
  components: { AppSideNavigation, AppHeader, AppFooter }
}
</script>