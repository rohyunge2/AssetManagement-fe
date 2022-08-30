<template>
  <div class="d-flex flex-column vh-100 bg-light container-fluid p-0">
    <nav class="navbar navbar-light bg-dark">
      <TitleHeader />
    </nav>
    <div class="d-flex flex-row flex-grow-1">
      <SideBar />
      <AssetManagement />
    </div>
  </div>
</template>

<script lang="ts">
import SideBar from "@/components/component/SideBar/SideBar.vue";
import TitleHeader from "@/components/component/TitleHeader/TitleHeader.vue";
import AssetManagement from "@/components/component/AssetManagement/AssetManagement.vue";
import { defineComponent } from "vue";

export default defineComponent({
  components: { SideBar, TitleHeader, AssetManagement },
});
</script>
