<template>
  <div class="about">
    <Database msg="This is an about page" />
  </div>
</template>

<script>
import Database from "@/components/Database.vue";

export default {
  name: "About",
  components: {
    Database,
  },
};
</script>
