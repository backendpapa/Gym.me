<template>
  <div>
      <v-container style="">
          <v-row justify="center" align="center"  style="width:100%" no-gutters>
              <v-col class="" cols="12" xl="2" lg="2"></v-col>
              <v-col class="" cols="12" xl="8" lg="8">
                
                     <div>
                          <div>
                      <v-img class="image" src="../../assets/images/users.png"></v-img>
                      <div style="padding-top:8%;padding-left:12%" class="">
                          <p class="font-weight-bold font-size-3">Our mission<span style="color:#4AE290">.</span></p>
                      </div>
                  </div>
                  <br>
                  <br>
                  <p class="font-size-10" style="color:#595962">We are distinguished by our unsurpassed motivating atmosphere, knowledgeable staff, and premier exercise equipment, which supports our members in meeting their individual fitness goals.
                    </p>
                    <br>
                    <p class="font-size-10" style="color:#595962">
                The strength of our heart-felt identity is utilized to inspire every person that steps foot into our gyms to better themselves.</p>
                     </div>
                     <v-btn text class="font-size-12 ml-n4 font-weight-bold" small> Join now <v-icon>mdi-chevron-right-circle</v-icon></v-btn>
                    
                 
              </v-col>
              <v-col class="" cols="12" xl="2" lg="2"></v-col>
          </v-row>
      </v-container>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.image{
    width:150px !important;
    position: absolute !important;
    margin-top: 2%;
}

@media screen and (max-width:500px) {
    .image{
    width:70px !important;
    position: absolute !important;
    margin-top: 7%;
}   
}
</style>