<template>
  <div>
      <div role="navigation" aria-label="Main" class="main-navbar">
          <div class="d-flex align-items-center">
            <img class="logo-navbar" src="../assets/icon.png" alt="Logo Jennifer">
            <div class="d-flex align-items-center ml-2">
                <h4 class="namefirst-navbar">JENNIFER</h4>
                <h4 class="namesecond-navbar ml-1">OENNING</h4>
            </div>
          </div>
      </div>
  </div>
</template>

<script>

export default {
  name: 'Header'
}
</script>

<style lang="css" scoped>
    .main-navbar {
        box-sizing: border-box;
        min-width: 0;
        border-bottom: 5px solid #dcadb3;
        margin-bottom: 4em;
        padding: 10px 8px 10px 8px;
        color: white;
        -webkit-align-items: center;
        -webkit-box-align: center;
        -ms-flex-align: center;
        align-items: center;
        display: -webkit-box;
        display: -webkit-flex;
        display: -ms-flexbox;
        display: flex;
        background-color: #272749;
    }
    .logo-navbar {
        width: 55px;
        height: 55px;
        border-radius: 100%;
    }
    
    .namefirst-navbar,
    .namesecond-navbar {
        font-weight: 700;
    }
    
    .namefirst-navbar {
        color: #dcadb3;
    }
</style>
