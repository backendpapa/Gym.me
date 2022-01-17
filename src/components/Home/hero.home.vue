<template>
  <div>
    <div style="height: 100vh" class="black">
      <v-row style="height: 100vh; position: absolute; width: 100%" no-gutters>
        <v-col cols="3" xl="5" lg="5"> </v-col>
        <v-col
          :style="`background:url(${require('../../assets/images/bg.png')});background-size:cover`"
          cols="9"
          xl="4"
          lg="4"
        >
        </v-col>
      </v-row>
      <v-container>
        <v-row
          style="height: 100vh; position: relative; z-index: 1"
          no-gutters
          align="center"
          justify="center"
        >
          <v-col cols="12" xl="6" lg="6">
            <p
              class="white--text font-size-2 font-weight-bold"
              style="line-height: 1"
            >
              Get the best part of your day <br /><span style="color: #4ae290">
                – you fit here.</span
              >
            </p>
            <p class="white--text font-size-8" style="line-height:1.4">
              We provide serious fitness but within <br> a fun and friendly, safe
              space.
            </p>
            <v-btn color="white" class="font-weight-bold" style="border-radius:0" large>JOIN NOW</v-btn>
          </v-col>
          <v-col cols="12" xl="6" lg="6" class="d-none d-sm-flex" />
        </v-row>
      </v-container>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>