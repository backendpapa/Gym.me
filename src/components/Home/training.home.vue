<template>
  <div>
       <v-container>
          <v-row no-gutters>
              <v-spacer></v-spacer>
                <div>
                      <v-img class="image2" src="../../assets/images/cal.png"></v-img>
                      <div style="padding-top:8%;" class="">
                          <p class="font-weight-bold font-size-3">Training programs<span style="color:#4AE290">.</span></p>
                      </div>
                  </div>
                  <v-spacer></v-spacer>
          </v-row>
       </v-container>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.image2{
    width:150px !important;
    position: absolute !important;
    margin-left: -7%;
    
}

@media screen and (max-width:500px) {
    .image2{
    width:70px !important;
    position: absolute !important;
    margin-left: -7%;
    margin-top:5%
}   
}
</style>