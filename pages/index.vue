<template>
  <div>
    <v-row justify="center" align="center">
      <v-col cols="12" sm="8" md="6">
        <div
          class="pa-7 white rounded-circle d-inline-block"
        >
          <v-icon large color="blue" dark>
            mdi-cloud-upload
          </v-icon>
        </div>
      </v-col>
    </v-row>
    <h1 style="margin-top:20px;">
      KNN BANK
    </h1>
    <h3>MOBILE APP</h3>
    <v-row>
      <v-container>
        <v-form>
          <v-col
            cols="12"
            sm="6"
            md="4"
          >
            <v-text-field
              label="PLEASE ENTER YOUR PASSWORD"
              placeholder="PASSWORD"
              filled
              rounded
              dense
            />
            <v-btn
              class="btn1"
            >
              <span class="txt1">LOGIN</span>
            </v-btn>
            <p>Forgot password?</p>
            <p>New to Bank Apps? sign Up</p>
          </v-col>
        </v-form>
      </v-container>
    </v-row>
  </div>
</template>
<style>
.bg{
  background: linear-gradient(to top right,#5842ff,#0989ff,#038fff);
  margin-top: 100px;
}
.h3{
  margin-bottom: 50px;
}
.txt1{
  color: brown;
}
.btn1{
  background: linear-gradient(to bottom,#ffeb3b,#ffc107);
  margin-bottom: 60px;
}

</style>
