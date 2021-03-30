<template>
  <div class="container-about">
      <div class="row mb-3">
          <div class="col-sm-7">
              <h1 class="text-left">JENNIFER OENNING</h1>
              <h3 class="text-left about-me">web developer & content creator</h3>
          </div>
          <div class="col-sm-4">
              <img class="w-100" src="../assets/logo.png" alt="Draw Jennifer">
          </div>
      </div>
      <div class="row">
          <p class="intro-about">Olá me chamo Jennifer, tenho 20 anos, moro em Santa Catarina, estou cursando Engenharia de Software e trabalho atualmente como Web Developer - 
              Full Stack. Tenho um canal no Youtube e faço lives pela Twitch! :D</p>
      </div>
  </div>
</template>

<script>

export default {
  name: 'About'
}
</script>

<style lang="css" scoped>
    .about-me {
        font-weight: 400;
        color: gray;
    }
    .intro-about {
        font-size: 1.1em;
        line-height: 1.5em;
        text-align: left;
    }
    .container-about {
        margin: 0 auto;
        max-width: 960px;
        padding: 0px 1.0875rem 1.45rem;
        padding-top: 0;
    }
    
</style>
