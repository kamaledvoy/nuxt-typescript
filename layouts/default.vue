<template>
  <div>
    <HeaderComponent />
    <Nuxt />
    <FooterComponent />
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "nuxt-property-decorator";
import HeaderComponent from "~/components/Header.vue";
import FooterComponent from "~/components/Footer.vue";

@Component({
  components: {
    HeaderComponent,
    FooterComponent,
  },
})
export default class DefaultLayout extends Vue {}
</script>
