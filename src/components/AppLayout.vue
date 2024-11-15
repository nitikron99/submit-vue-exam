<template>
  <div>
    <aside
      class="sidenav navbar navbar-vertical navbar-expand-xs border-0 border-radius-xl my-3 fixed-start ms-3"
    >
      <SidebarComponent />
    </aside>
    <main class="main-content">
      <DashboardPage />
    </main>
  </div>
</template>

<script>
import SidebarComponent from "./SidebarComponent.vue";
import DashboardPage from "./DashboardPage.vue";
export default {
  components: {
    SidebarComponent,
    DashboardPage,
  },
};
</script>

<style></style>
