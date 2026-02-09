<template>
  <div>
    <h1>Welcome to My Nuxt App</h1>
    <v-btn>Submit</v-btn>

    <v-row>
      <v-col cols="12" md="3">
        <v-card height="150" color="blue">
          <v-card-text>
            <v-row>
              <v-col cols="6">
                <v-icon size="100">mdi-currency-usd</v-icon>
              </v-col>
              <v-col cols="6">
                <v-row>
                  <v-col cols="12" class="text-h6">
                    Ammount
                  </v-col>

                  <v-col cols="12" class="text-h3">
                    250
                  </v-col>
                </v-row>
              </v-col>
            </v-row>



          </v-card-text>

        </v-card>
      </v-col>

      <v-col cols="12" md="3">

        <v-card height="150" color="red">

          <v-card-text>

            <v-row>
              <v-col cols="6">
                <v-sheet color="white" height="90"></v-sheet>
              </v-col>

              <v-col cols="6">
                <v-row dense>
                  <v-col cols="12">

                    <v-sheet color="white" height="40"></v-sheet>

                  </v-col>
                  <v-col cols="12">

                    <v-sheet color="white" height="40"></v-sheet>

                  </v-col>
                </v-row>
              </v-col>
            </v-row>

          </v-card-text>

        </v-card>

      </v-col>

      <v-col cols="12" md="3">
        <v-card height="150" color="yellow"></v-card>
      </v-col>

      <v-col cols="12" md="3">
        <v-card height="150" color="orange"></v-card>
      </v-col>

    </v-row>
  </div>


</template>

<script lang="ts" setup>
</script>

<style></style>