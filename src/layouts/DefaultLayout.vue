<template>
  <Header />
  <slot />
  <Footer />
</template>
<script>
import Header from "../components/NavigationHeader.vue";
import Footer from "../components/NavigationFooter.vue";
export default {
  components: {
    Header,
    Footer,
  },
};
</script>
