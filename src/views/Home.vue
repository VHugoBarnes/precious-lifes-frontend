<template>
  <div class="home">
    <Header></Header>
  </div>
</template>

<script>
// @ is an alias to /src
import Header from "@/components/utils/Header.vue";

export default {
  name: "Home",
  components: {
    Header,
  },
};
</script>
