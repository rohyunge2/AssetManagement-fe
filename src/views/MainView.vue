<template>
  <main>
    <MainLayout />
  </main>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";
import MainLayout from "@/components/layout/MainLayout.vue"; // @ is an alias to /src

@Options({
  components: {
    MainLayout,
  },
})
export default class MainView extends Vue {}
</script>
