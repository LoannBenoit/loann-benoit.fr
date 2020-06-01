<template>
  <div class="row">
    <div class="md-layout md-gutter md-alignment-center">
      <md-tabs md-sync-route md-alignment="centered">
        <md-tab v-bind:class="test" id="tab-home" md-label="accueil" to="#home"></md-tab>
        <md-tab id="tab-more" md-label="A PROPOS" to="#more"></md-tab>
        <md-tab id="tab-portfolio" md-label="PORTFOLIO"></md-tab>
        <md-tab id="tab-contact" md-label="ME CONTACTER"></md-tab>
      </md-tabs>
    </div>
  </div>
</template>

<script>
export default {
  name: "Navbar",
  // props: {
  //     text
  // },
  data: function() {
    return {};
  },
  methods: {},
  mounted() {}
};
</script>

<style lang="scss">

html,
body {
  color: white;
}

</style>