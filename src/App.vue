<template>
  <v-app id="teste-roga">
    <v-app-bar
        app
    >
      <div style="padding-left: 1000px;">
        John Doe
      </div>
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
              <div style="padding: 25px; padding-top: 50px;">
                <img
                    class="avatarB"
                    alt
                    src="https://cdn.pixabay.com/photo/2020/06/24/19/12/cabbage-5337431_1280.jpg"/>
              </div>

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

<style>
  .avatarB{
    border-radius: 60%;
    width: 60px;
    height: 60px;
  }
</style>