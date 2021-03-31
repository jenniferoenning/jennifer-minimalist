<template>
    <div class="d-flex mt-3">
        <ul class="sociais-bio">
            <li>
                <a :href="urlGithub">
                    <img class="bioicon-github" src="../assets/github.svg" alt="Github icon">
                </a>
            </li>
            <li>
                <a :href="urlLinkedin">
                    <img class="bioicon-linkedin" src="../assets/linkedin.svg" alt="Linkedin icon">
                </a>
            </li>
            <li>
                <a :href="urlTwitter">
                    <img class="bioicon-twitter" src="../assets/twitter.svg" alt="Twitter icon">
                </a>
            </li>
            <li>
                <a :href="urlTwitch">
                    <img class="bioicon-twitch" src="../assets/twitch.svg" alt="Twitch icon">
                </a>
            </li>
            <li>
                <a :href="urlInstagram">
                    <img class="bioicon-instagram" src="../assets/instagram.svg" alt="Instagram icon">
                </a>
            </li>
            <li>
                <a :href="urlYoutube">
                    <img class="bioicon-youtube" src="../assets/youtube.svg" alt="Youtube icon">
                </a>
            </li>
        </ul>
    </div>
</template>

<script>
export default {
  name: 'Social',
  data () {
      return {
        urlGithub: "https://github.com/jenniferoenning",
        urlLinkedin: "https://linkedin.com/in/jennifer-stang-oenning/",
        urlTwitter: "https://twitter.com/JenniferOenning",
        urlTwitch: "https://twitch.tv/jenni",
        urlInstagram: "https://instagram.com/jenniferoenning/",
        urlYoutube: "https://youtube.com/c/jenniferoenningg"
    }
  }
}
</script>

<style lang="css" scoped>
    
    .sociais-bio {
        list-style: none;
        display: inline-flex;
        padding: 0px;
    }
    
    .bioicon-github,
    .bioicon-linkedin,
    .bioicon-twitter,
    .bioicon-twitch,
    .bioicon-instagram,
    .bioicon-youtube {
        filter: invert(41%) sepia(107%) saturate(0%) hue-rotate(87deg) brightness(88%) contrast(42%);
        width: 24px;
        height: 30px;
        margin-right: 15px;
    }
    .bioicon-github:hover,
    .bioicon-linkedin:hover,
    .bioicon-twitter:hover,
    .bioicon-twitch:hover,
    .bioicon-instagram:hover,
    .bioicon-youtube:hover {
        filter: invert(41%) sepia(107%) saturate(0%) hue-rotate(87deg) brightness(40%) contrast(42%);
    }
</style>
