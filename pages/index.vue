<template>
  <div>
    <v-container>
      <v-row>
        <v-col cols="12" md="6" lg="3">
          <div class="box"></div>
        </v-col>
        <v-col cols="12" md="6" lg="3">
          <div class="box"></div>
        </v-col>
        <v-col cols="12" md="6" lg="3">
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
    console.log("!!");
    console.log(this.$vuetify);
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
