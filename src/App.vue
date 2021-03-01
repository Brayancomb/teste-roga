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
              v-for="n in 1"
              :key="n"
              cols="3"
              >
          <v-card
              height="200"
              width="400"
              elevation="3">
              <div style="padding: 25px; padding-top: 32px;" class="picUser">
                <img
                    class="avatarB"
                    alt
                    src="https://cdn.pixabay.com/photo/2020/06/24/19/12/cabbage-5337431_1280.jpg"/>
                <div class="infoUser">
                  João Doria
                  <div class="lastVisual">
                    Ultima Vizualização: 01/01/2000
                  </div>
                </div>
              </div>
              <v-divider></v-divider>
              <div class="infoEdit">
                <div class="onlypadd">
                  <div clas="emailInfo">Email</div>
                    <div class="comboInfos">idade
                      <div class="cellinfo">celular</div>
                    </div>
                </div>
                <div>
                  <v-btn fab icon>
                    <v-icon
                       color="primary"
                       x-large
                       size="40">
                       mdi-pencil-circle
                    </v-icon>
                  </v-btn>
                 <v-btn
                    fab
                    icon>
                      <v-icon
                        color="primary">
                        mdi-dots-vertical
                      </v-icon>
                  </v-btn>
                </div>
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
  data: () => ({

  })
}
</script>

<style>
  .avatarB{
    border-radius: 60%;
    width: 60px;
    height: 60px;
  }
  .picUser{
    display: flex;
    align-content: center;
    align-items: center;
    align-self: center;
  }
  .infoUser{
    padding-left: 16px;
    font-size: 25px;
    font-family: "Roboto", sans-serif;
  }
  .infoEdit{
    display: flex;
    align-content: center;
    align-items: center;
    align-self: center;
  }
  .onlypadd{
    padding-left: 20px;
  }

  .comboInfos{
    display: flex;
    align-content: center;
    align-items: center;
    align-self: center;
  }
  .lastVisual{
    font-size: 14px;
    opacity: 60%;
  }
  .cellinfo{
    padding-left: 16px;
  }


</style>