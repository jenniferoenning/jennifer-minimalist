<template>
  <div class="container-about">
      <div class="row mb-3">
          <div class="col-sm-7">
            <h1 class="text-left">{{ name }}</h1>
            <h3 class="text-left about-me">{{ worker }}</h3>
            <Social />
          </div>
          <div class="col-sm-5">
              <img class="w-100" src="../assets/logo.png" alt="Draw Jennifer">
          </div>
      </div>
      <div class="row">
          <p class="intro-about">{{ message }}</p>
      </div>
  </div>
</template>

<script>

import Social from './Social.vue'

export default {
    name: 'About',
    components: {
        Social
    },
    data () {
        return {
            name: "JENNIFER OENNING",
            worker: "web developer & content creator",
            message: "Olá seja bem vindo ao meu cantinho! Me chamo Jennifer Oenning, tenho 20 anos e eu sou extremamente apaixonada por tecnologia e games, atualmente estou no setor de desenvolvimento web como full stack na empresa Bw2 Tecnologia, também sou criadora de conteúdo na plataforma da Twitch e Youtube, construi este site pra vocês conhecerem um pouquinho de mim e conhecer meus projetos, eles são totalmente códigos abertos para quaisquer opiniões ou mudanças, quero criar aqui algumas matérias de tecnologias, tutoriais, espero que vocês gostem e se quiser me seguir nas redes sociais vou deixar logo a baixo :D",
        }
    }
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
