<template>
  <div class="sideNavigation">
    <div>
      <ul>
        <router-link to="/menu1">
          <li>menu1</li>
        </router-link>
        <router-link to="/menu2">
          <li>menu2</li>
        </router-link>
        <router-link to="/menu3">
          <li>menu3</li>
        </router-link>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "SideNavigation"
}
</script>

<style scoped>

</style>