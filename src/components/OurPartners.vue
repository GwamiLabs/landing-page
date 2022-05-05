<template>
  <section id="Partners" class="partners-page" 
      style="
      background-color:#F3FCE2;
      text-align: center;">
    <div class="container-fluid">
    <h1 class="partner-page-title">
      <span>
        <img src="../assets/PageFour/Text-framer-emdash.svg"/>
      </span>        
      Our Partners
      <span>
        <img src="../assets/PageFour/Text-framer-emdash.svg"/>
      </span> 
    </h1>
    <div class="container-fluid" 
      style="
      max-width:1690px
      padding-left:0px;
      padding-right:0px;
      padding-top:76px; 
      padding-bottom:119px;">
    <div class="row d-flex float-center align-items-center bg-transparent"
    style="padding-top:76px; padding-bottom:119px;">
      <div class="card col">
      <a class="partner-logo-link" target="_blank" href="https://www.klimadao.finance/">
        <img class="partner-Logo" src="../assets/PageFour/Klima-Logo-1.svg"/>
      </a>
      </div>
      <div class="card col">
      <a class="partner-logo-link text-nowrap" target="_blank" href="https://punk.domains">
        <img class="punk-logo-img img-fluid" src="@/assets/punk/punk-logo512.png" />
        <span class="punk-logo-text">Punk Domains</span>
      </a>
      </div>
      <div class="card col">
      <a class="partner-logo-link" target="_blank" href="https://verify.onsetcarbon.com/">
        <img class="partner-Logo" src="../assets/PageFour/Onset-Carbon.svg"/>
      </a>
      </div>
      <div class="card col">
      <a class="partner-logo-link" target="_blank" href="https://carbonwallet.earth/">
        <img class="partner-Logo" src="../assets/PageFour/Carbon-Wallet-Logo.svg"/>
      </a>
      </div>
    </div>
    </div>
    </div>

    
  </section>
</template>

<script>
export default {
  name: 'OurPartners',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.partner-logo-link{
  margin-top:52px;
  margin-bottom:52px;
  margin-left:52px;
  margin-right:52px;
  text-decoration: none;
}

.card {
        margin: 32px; /* Added */
        float: center;
        margin-top: 71px;
        min-height:210px;
        min-width: 260px;
        width: 260px;
        background-color: transparent;
        border:1px transparent;
}

.partner-page-title {
        color:#202832; 
        padding-top:70px; 
        font-size:36px;
}


.partner-Logo {

  width: 186px;
}

/* Punk Domains */
@font-face { 
  font-family: "Cyber";
  src: url("@/assets/punk/Cyber.ttf"); 
}

.punk-logo-img {
  width: 2em;
  margin-right: 5px;
  vertical-align: top;
}

.punk-logo-text {
  font-family: 'Cyber', cursive;
  font-size: 1.5em;
  color: black;
  vertical-align: sub;
}
/* END Punk Domains */
</style>
