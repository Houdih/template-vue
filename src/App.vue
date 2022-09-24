<template>
  <NavBase />
  <router-view />
  <FooterBase />
</template>

<script>
// @ is an alias to /src
import NavBase from "@/components/NavBase.vue";
import FooterBase from "@/components/FooterBase.vue";

export default {
  components: { NavBase, FooterBase },
};
</script>
