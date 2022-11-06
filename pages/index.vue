<template>
  <div>
    <v-container>
      <v-row>
        <v-col cols="12" sm="6" md="4" lg="3">
          <div class="box"></div>
        </v-col>
        <v-col cols="12" sm="6" md="4" lg="3">
          <div class="box"></div>
        </v-col>
        <v-col cols="12" sm="6" md="4" lg="3">
          <div class="box"></div>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>

<script>
export default {
  name: "IndexPage",
  mounted() {
    console.log(this.$vuetify.breakpoint);
  },
};
</script>

<style lang="scss" scoped>
.box {
  width: 100%;
  height: 50px;
  background: black;
}
</style>
