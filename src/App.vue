<template>
  <v-app id="teste-roga">
    <v-app-bar
        app
    >
      <div style="
        padding-left: 1000px;"
      >John Doe</div>
    </v-app-bar>

    <v-main>
      <v-container>
        <v-row>
          <v-col
              v-for="n in 3"
              :key="n"
              cols="4"
              >
          <v-card
              height="200"
              width="400"
              elevation="6">
              <v-avatar

                color="teal"
                size="60"
                rounded
              > HI </v-avatar>
          </v-card>
          </v-col>
        </v-row>
      </v-container>
    </v-main>
  </v-app>
</template>

<script>
export default {
  //
}
</script>