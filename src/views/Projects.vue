<template>
<div class="main">
    
    
    <div class="projects-one container row">
        <h2><router-link style="text-decoration:none;" to="/">Go back</router-link></h2>
        <h3>Ordered by most recent</h3>
        <div class="col-xl-2 col-md-0"></div>
        <div class="col-xl-12 col-md-12">
  <b-card-group>
    <b-card title="Sony Creator Space NY" :img-src="require('../assets/creatorSpace.png')" img-alt="Image" img-top>
      <b-card-text>
        Created this page using jQuery, HTML and SCSS, imported to Zesty CMS, made customizable using Parsley templating language. Attached to Sony's Alpha Universe.
      </b-card-text>
            <b-button variant="outline-dark" href="https://alphauniverse.com/creative-space-nyc/">Visit site</b-button>

      <template v-slot:footer>
        <!-- <small class="text-muted">Last updated 3 mins ago</small> -->
      </template>
    </b-card>
    <b-card title="Concur localization for 22 languages" :img-src="require('../assets/concur.png')"  img-alt="Image" img-top>
      <b-card-text>
        Led development effort for implementing localization functionality for 22 languages, as well as importing trasnlation, adjusting UI and maintaining clean and organized git flows. Built using Vue, SASS, Bootstrap and Webpack.
      </b-card-text>
      <b-button variant="outline-dark" href="https://www.concur.com/self-guided-demo-expense#/">Visit site</b-button>
      <template v-slot:footer>
        <!-- <small class="text-muted">Last updated 3 mins ago</small> -->
      </template>
    </b-card>
    <b-card title="Microsoft Health and Security Compliance" :img-src="require('../assets/healthSecurity1.png')" img-alt="Image" img-top>
      <b-card-text>
        This was through Indigo Slate, for Microsoft. I constructed this SPA using Vue, SASS, Bootstrap, and Webpack
      </b-card-text>
                  <b-button variant="outline-dark" href="https://discover.microsoft.com/data-security-privacy-and-compliance-for-healthcare/#/">Visit site</b-button>

      <template v-slot:footer>
        <!-- <small class="text-muted">Last updated 3 mins ago</small> -->
      </template>
    </b-card>
  </b-card-group>
  </div>
  <div class="col-xl-2 col-md-0"></div>
</div>
<div class="projects-two container row">
        <h2></h2>
        <!-- <div class="col-xl-2 col-md-0"></div> -->
        <div class="col-xl-12 col-md-12">
  <b-card-group>
    <b-card title="Dell Technologies localization" :img-src="require('../assets/dellWall.png')" img-alt="Image" img-top>
      <b-card-text>
        Led the development effort on creating functionality for localization in Mandarin.
        Built using Vue, Vanilla Javascript,  SASS, and Webpack
      </b-card-text>
                  <b-button variant="outline-dark" href="https://www.vmwareiotsolutions.com/">Visit site</b-button>

      <template v-slot:footer>
        <!-- <small class="text-muted">Last updated 3 mins ago</small> -->
      </template>
    </b-card>

    <b-card title="Nintex Guided demo" :img-src="require('../assets/nintex.png')" img-alt="Image" img-top>
      <b-card-text>
        Added multiple features such as progress tracking, state management, and other UI components. 
        Built using Vue, SASS, Bootstrap and Webpack
      </b-card-text>
                  <b-button variant="outline-dark" href="https://www.nintex.com/guided-tour/#/manage/process-management/intro/">Visit site</b-button>

      <template v-slot:footer>
        <!-- <small class="text-muted">Last updated 3 mins ago</small> -->
      </template>
    </b-card>
    <b-card title="Microsoft Health Collaboration" :img-src="require('../assets/healthColab1.png')" img-alt="Image" img-top>
      <b-card-text>
                This was through Indigo Slate, for Microsoft. I constructed this SPA using Vue, SASS, Bootstrap, and Webpack

      </b-card-text>
            <b-button variant="outline-dark" href="https://discover.microsoft.com/empower-your-clinicians-with-microsoft-teams/#/">Visit site</b-button>

      <template v-slot:footer>
        <!-- <small class="text-muted">Last updated 3 mins ago</small> -->
      </template>
    </b-card>
  </b-card-group>
  </div>
  <!-- <div class="col-xl-2 col-md-0"></div> -->
</div>
<div class="projects-three container row">
        <h2></h2>
        <!-- <div class="col-xl-2 col-md-0"></div> -->
        <div class="col-xl-12 col-md-12">
  <b-card-group>
    <b-card title="Trendly" :img-src="require('../assets/trendly.png')" img-alt="Image" img-top>
      <b-card-text>
        Trendly is a RESTful API that connects users via (Short Message Service) SMS to Meetup (https://www.meetup.com/). This app allows users to sign up with their Meetup User ID via text message. Once signed up, users will automatically receive a text notification 24 hours before any of their upcoming meetup events. 
      </b-card-text>
                  <b-button variant="outline-dark" href="https://github.com/Meetup-Trendly/trendly-server">Visit site</b-button>

      <template v-slot:footer>
        <!-- <small class="text-muted">Last updated 3 mins ago</small> -->
      </template>
    </b-card>

    <b-card title="Geo-Jumper" :img-src="require('../assets/geo-jump.png')" img-alt="Image" img-top>
      <b-card-text>
        Geo-Jumper is a multiplayer fullstack platform game that combines socket.io with a frontend React library. This application is designed to create a unique game experience by matching online users to race to the finish line and be the first to catch the star. This application showcases a multiplayer/multi-level game and persists user data using MongoDB.
      </b-card-text>
                  <b-button variant="outline-dark" href="https://geo-jumper-frontend.herokuapp.com">Play now!</b-button>

      <template v-slot:footer>
        <!-- <small class="text-muted">Last updated 3 mins ago</small> -->
      </template>
    </b-card>

    <b-card title="Smackitball" :img-src="require('../assets/smackitball.png')" img-alt="Image" img-top>
      <b-card-text>
        Smackitball is a sci-fi themed racket sport designed from the ground up for virtual reality. I worked on the intial prototype entually leading to this final deployed verison. Built using Unity, C#, Javascript. 
      </b-card-text>
                  <b-button variant="outline-dark" href="https://store.steampowered.com/app/461320/Smackitball/">Steam link</b-button>

      <template v-slot:footer>
        <!-- <small class="text-muted">Last updated 3 mins ago</small> -->
      </template>
    </b-card>
  </b-card-group>
  </div>
  <!-- <div class="col-xl-2 col-md-0"></div> -->
</div>
</div>
</template>
<style lang="scss" scoped>
.main{

    margin-bottom:40px;
    .row{
        padding:0;
        margin:auto;
    }
}
h2{
  padding-left:15px;
  font-size:20px;
  margin-top:30px;
  
}
h3{
    padding-left:15px;
  font-size:14px;
  margin-top:34px;
}
a{
    color:black;
}
</style>