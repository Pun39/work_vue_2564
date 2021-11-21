<template>
  <v-parallax
    dark
    src="https://p0.pikist.com/photos/596/263/background-abstract-abstract-background-colorful-abstract-background-digital-style-light.jpg"
  >
    <h2> Sing up your bank account</h2>
    <div>
      <v-text-field
        label="Your name"
        hide-details="auto"
      />
      <v-text-field
        label="Bank Account"
        hide-details="auto"
      />
      <v-text-field
        label="Mobile phone number"
        hide-details="auto"
      />
      <v-text-field
        label="Email"
        hide-details="auto"
      />
      <v-text-field
        label="Password"
        hide-details="auto"
      />
    </div><br>
    <v-checkbox
      :rules="[v => !!v || 'You must agree to continue!']"
      label="By signing up, you agree to Bank's Term of Use &amp; Privacy Policy."
      required
    />
    <v-row>
      <v-col class="d-flex justify-center ">
        <v-btn class="btn1" color="yellow lighten-4">
          <span style="color: brown">SIGN UP</span>
        </v-btn> &nbsp; &nbsp; &nbsp;
        <h3>or</h3> &nbsp; &nbsp; &nbsp;
        <v-btn class="btn2" color="transparent">
          <span>CANCEL</span>
        </v-btn>
      </v-col>
    </v-row>
    <v-row>
      <p>Already Signed up? Login</p>
    </v-row>
  </v-parallax>
</template>
<style>

</style>
