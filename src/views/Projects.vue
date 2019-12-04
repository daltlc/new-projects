<template>
  <div class="main">
    <div class="main__projects container row">
      <h2><router-link style="text-decoration:none;" to="/">Go back</router-link></h2>
      <!-- <h3>Professional Work</h3> -->
      <div class="col-xl-12 col-md-12">
        <div>
          <b-card-group style="margin-bottom:40px;" deck>
            <b-card
              title="Sony NYC Creator Space"
              :img-src="require('../assets/creatorSpace.png')"
              img-alt="Image"
              img-top
            >
              <b-card-text>
                <img style="width:60%;" src="../assets/sony.png" alt="" />
              </b-card-text>
              <template v-slot:footer>
                <!-- <small class="text-muted">Last updated 3 mins ago</small> -->
                <div class="icons">
                  <img class="skill-icon" src="../assets/html.png" alt="" />
                  <img class="skill-icon" src="../assets/sass.png" alt="" />
                  <img class="skill-icon" src="../assets/js.png" alt="" />
                  <img class="skill-icon" src="../assets/jquery.png" alt="" />
                  <img class="skill-icon" src="../assets/bootstrap.png" alt="" />
                  <img class="skill-icon" src="../assets/zesty.png" alt="" />
                </div>
                <b-button variant="outline-dark" href="https://alphauniverse.com/creative-space-nyc/"
                  >Visit site</b-button
                >
              </template>
            </b-card>

            <b-card
              title="Health and Security"
              :img-src="require('../assets/healthColab1.png')"
              img-alt="Image"
              img-top
            >
              <b-card-text>
                <img style="width:60%;" src="../assets/microsoft.png" alt="" />
              </b-card-text>
              <template v-slot:footer>
                <!-- <small class="text-muted">Last updated 3 mins ago</small> -->
                <div class="icons">
                  <img class="skill-icon" src="../assets/vue.png" alt="" />
                  <img class="skill-icon" src="../assets/sass.png" alt="" />
                  <img class="skill-icon" src="../assets/js.png" alt="" />
                  <img class="skill-icon" src="../assets/webpack.png" alt="" />
                  <img class="skill-icon" src="../assets/bootstrap.png" alt="" />
                  <img class="skill-icon" src="../assets/wordpress.png" alt="" />
                </div>
                <b-button
                  variant="outline-dark"
                  href="https://discover.microsoft.com/data-security-privacy-and-compliance-for-healthcare/#/"
                  >Visit site</b-button
                >
              </template>
            </b-card>

            <b-card
              title="Health Collaboration"
              :img-src="require('../assets/healthSecurity1.png')"
              img-alt="Image"
              img-top
            >
              <b-card-text>
                <img style="width:60%;" src="../assets/microsoft.png" alt="" />
              </b-card-text>
              <template v-slot:footer>
                <!-- <small class="text-muted">Last updated 3 mins ago</small> -->
                <div class="icons">
                  <img class="skill-icon" src="../assets/vue.png" alt="" />
                  <img class="skill-icon" src="../assets/sass.png" alt="" />
                  <img class="skill-icon" src="../assets/js.png" alt="" />
                  <img class="skill-icon" src="../assets/webpack.png" alt="" />
                  <img class="skill-icon" src="../assets/bootstrap.png" alt="" />
                  <img class="skill-icon" src="../assets/wordpress.png" alt="" />
                </div>
                <b-button
                  variant="outline-dark"
                  href="https://discover.microsoft.com/empower-your-clinicians-with-microsoft-teams/"
                  >Visit site</b-button
                >
              </template>
            </b-card>
          </b-card-group>
        </div>
        <div>
          <b-card-group style="margin-bottom:40px;" deck>
            <b-card
              title="VMWare | Dell Future City"
              :img-src="require('../assets/dellWall.png')"
              img-alt="Image"
              img-top
            >
              <b-card-text>
                <img style="width:60%;" src="../assets/vmware1.png" alt="" />
              </b-card-text>
              <template v-slot:footer>
                <!-- <small class="text-muted">Last updated 3 mins ago</small> -->
                <div class="icons">
                  <img class="skill-icon" src="../assets/vue.png" alt="" />
                  <img class="skill-icon" src="../assets/sass.png" alt="" />
                  <img class="skill-icon" src="../assets/js.png" alt="" />
                  <img class="skill-icon" src="../assets/webpack.png" alt="" />
                </div>
                <b-button
                  variant="outline-dark"
                  href="https://discover.microsoft.com/data-security-privacy-and-compliance-for-healthcare/#/"
                  >Visit site</b-button
                >
              </template>
            </b-card>

            <b-card title="Nintex Guided-demo" :img-src="require('../assets/nintex.png')" img-alt="Image" img-top>
              <b-card-text>
                <img style="width:60%;" src="../assets/nintexbig.png" alt="" />
              </b-card-text>
              <template v-slot:footer>
                <!-- <small class="text-muted">Last updated 3 mins ago</small> -->
                <div class="icons">
                  <img class="skill-icon" src="../assets/vue.png" alt="" />
                  <img class="skill-icon" src="../assets/sass.png" alt="" />
                  <img class="skill-icon" src="../assets/js.png" alt="" />
                  <img class="skill-icon" src="../assets/webpack.png" alt="" />
                </div>
                <b-button
                  variant="outline-dark"
                  href="https://www.nintex.com/guided-tour/#/manage/process-management/intro/"
                  >Visit site</b-button
                >
              </template>
            </b-card>

            <b-card title="Concur Guided-demo" :img-src="require('../assets/concur.png')" img-alt="Image" img-top>
              <b-card-text>
                <img style="width:60%;background-color:black;padding:5px;" src="../assets/concurlong.png" alt="" />
              </b-card-text>
              <template v-slot:footer>
                <!-- <small class="text-muted">Last updated 3 mins ago</small> -->
                <div class="icons">
                  <img class="skill-icon" src="../assets/vue.png" alt="" />
                  <img class="skill-icon" src="../assets/sass.png" alt="" />
                  <img class="skill-icon" src="../assets/js.png" alt="" />
                  <img class="skill-icon" src="../assets/webpack.png" alt="" />
                </div>
                <b-button variant="outline-dark" href="https://www.concur.com/self-guided-demo-expense#"
                  >Visit site</b-button
                >
              </template>
            </b-card>
          </b-card-group>
        </div>
        <div>
          <b-card-group style="margin-bottom:40px;" deck>
            <b-card title="Epic" :img-src="require('../assets/EPIC.png')" img-alt="Image" img-top>
              <b-card-text> </b-card-text>
              <template v-slot:footer>
                <!-- <small class="text-muted">Last updated 3 mins ago</small> -->
                <div class="icons">
                  <img class="skill-icon" src="../assets/html.png" alt="" />
                  <img class="skill-icon" src="../assets/js.png" alt="" />
                  <img class="skill-icon" src="../assets/jquery.png" alt="" />
                  <img class="skill-icon" src="../assets/sass.png" alt="" />

                  <img class="skill-icon" src="../assets/bootstrap.png" alt="" />
                </div>
                <b-button variant="outline-dark" href="https://epicraves.com"
                  >Visit site</b-button
                >
              </template>
            </b-card>

            <b-card title="Scope" :img-src="require('../assets/SCOPE.png')" img-alt="Image" img-top>
              <b-card-text> </b-card-text>
              <template v-slot:footer>
                <!-- <small class="text-muted">Last updated 3 mins ago</small> -->
                <div class="icons">
                  <img class="skill-icon" src="../assets/svelte.png" alt="" />
                  <img class="skill-icon" src="../assets/js.png" alt="" />
                  <img class="skill-icon" src="../assets/html.png" alt="" />
                                    <img class="skill-icon" src="../assets/sass.png" alt="" />

                </div>
                <b-button variant="outline-dark" href="https://svelte-pi.netlify.com"
                  >Visit site</b-button
                >
              </template>
            </b-card>

            <b-card title="Lavish Ent." :img-src="require('../assets/lavishent.png')" img-alt="Image" img-top>
              <b-card-text> </b-card-text>
              <template v-slot:footer>
                <!-- <small class="text-muted">Last updated 3 mins ago</small> -->
                <div class="icons">
                  <img class="skill-icon" src="../assets/vue.png" alt="" />
                  <img class="skill-icon" src="../assets/sass.png" alt="" />
                  <img class="skill-icon" src="../assets/js.png" alt="" />
                  <img class="skill-icon" src="../assets/webpack.png" alt="" />
                  <img class="skill-icon" src="../assets/bootstrap.png" alt="" />
                </div>
                <b-button variant="outline-dark" href="https://lavishentertainmentinc.com">Visit site</b-button>
              </template>
            </b-card>
          </b-card-group>
        </div>
        <div>
          <b-card-group style="margin-bottom:40px;" deck>
            <b-card title="Trendly" :img-src="require('../assets/trendly.png')" img-alt="Image" img-top>
              <b-card-text> </b-card-text>
              <template v-slot:footer>
                <!-- <small class="text-muted">Last updated 3 mins ago</small> -->
                <div class="icons">
                  <img class="skill-icon" src="../assets/js.png" alt="" />
                  <img class="skill-icon" src="../assets/node.png" alt="" />
                  <img class="skill-icon" src="../assets/twilio.png" alt="" />
                  <img class="skill-icon" src="../assets/mongo.png" alt="" />
                </div>
                <b-button variant="outline-dark" href="https://github.com/Meetup-Trendly/trendly-server"
                  >Visit Repo</b-button
                >
              </template>
            </b-card>

            <b-card title="Smackitball" :img-src="require('../assets/smackitball.png')" img-alt="Image" img-top>
              <b-card-text> </b-card-text>
              <template v-slot:footer>
                <!-- <small class="text-muted">Last updated 3 mins ago</small> -->
                <div class="icons">
                  <img class="skill-icon" src="../assets/js.png" alt="" />
                  <img class="skill-icon__unity" src="../assets/unity.png" alt="" />
                </div>
                <b-button variant="outline-dark" href="https://store.steampowered.com/app/461320/Smackitball/"
                  >Visit site</b-button
                >
              </template>
            </b-card>

            <b-card title="Geo-Jumper" :img-src="require('../assets/geo-jump.png')" img-alt="Image" img-top>
              <b-card-text> </b-card-text>
              <template v-slot:footer>
                <!-- <small class="text-muted">Last updated 3 mins ago</small> -->
                <div class="icons">
                  <img class="skill-icon" src="../assets/react.png" alt="" />
                  <img class="skill-icon" src="../assets/sass.png" alt="" />
                  <img class="skill-icon" src="../assets/js.png" alt="" />
                  <img class="skill-icon" src="../assets/webpack.png" alt="" />
                  <img class="skill-icon" src="../assets/node.png" alt="" />
                  <img class="skill-icon" src="../assets/mongo.png" alt="" />
                </div>
                <b-button variant="outline-dark" href="https://geo-jumper-frontend.herokuapp.com">Play Now!</b-button>
              </template>
            </b-card>
          </b-card-group>
        </div>
      </div>
    </div>
  </div>
</template>
<style lang="scss" scoped>
.main {
  margin-bottom: 40px;
  &__projects {
  }
  .row {
    padding: 0;
    margin: auto;
  }
}
h2 {
  padding-left: 15px;
  font-size: 20px;
  margin-top: 30px;
}
h3 {
  padding-left: 15px;
  font-size: 14px;
  margin-top: 34px;
}
a {
  color: black;
  &:hover {
    color: rgb(247, 129, 100);
    transition: all 0.2s ease-in-out;
  }
}
.skill-icon {
  width: 30px;
  margin: 15px 0px;
  padding: 0px 4px;
  &__unity {
    width: 50px;
  }
}
</style>
