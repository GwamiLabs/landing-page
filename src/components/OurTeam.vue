<template>
  <section
    id="Team"
    class="Team-Page"
    style="
      background-color: #fcfff8;
      text-align: center;
      max-width: 1440px;
      margin: auto;
    "
  >
    <h1 class="team-page-title">
      <span>
        <img src="../assets/PageThree/Text-framer-emdash.svg" />
      </span>
      Our Team
      <span>
        <img src="../assets/PageThree/Text-framer-emdash.svg" />
      </span>
    </h1>

    <div class="container-fluid team-cards-holder">
      <div class="d-none d-lg-block leaves-left">
        <img class="img-fluid" src="../assets/PageThree/Left-Leaf.svg" />
      </div>
      <div
        class="row mt-5 row-cols-3 align-items-center justify-content-center"
      >
        <div class="card col">
          <div class="card-body">
            <img
              class="card-img-top"
              src="../assets/PageThree/TimmyKlima.svg"
              alt="image-photo"
            />
            <h5 class="card-title">Timmy</h5>
            <span>Founder of Gwami and KlimaDAO contributor</span>
            <div class="card-twitter-icon">
              <a href="https://twitter.com/TimmyDC_">
                <TwitterBird />
              </a>
            </div>
          </div>
        </div>
        <div class="card col">
          <div class="card-body">
            <img
              class="card-img-top"
              src="../assets/PageThree/Rajasmasala.svg"
              alt="image-photo"
            />
            <h5 class="card-title">Rajasmasala</h5>
            <span>Lead developer for Gwami</span>
            <div class="card-twitter-icon">
              <a href="https://twitter.com/rajasmasala">
                <TwitterBird />
              </a>
            </div>
          </div>
        </div>
        <div class="card col">
          <div class="card-body">
            <img
              class="card-img-top"
              src="../assets/PageThree/SlaptainShwirv.svg"
              alt="image-photo"
            />
            <h5 class="card-title">SlaptainShwirv</h5>
            <span>Community Lead for Gwami</span>
            <div class="card-twitter-icon">
              <a href="https://twitter.com/SlaptainShwirv">
                <TwitterBird />
              </a>
            </div>
          </div>
        </div>
        <div class="card col">
          <div class="card-body">
            <img
              class="card-img-top"
              src="../assets/PageThree/Tigerlily.svg"
              alt="image-photo"
            />
            <h5 class="card-title">Tigerlily</h5>
            <span>Marketing lead for Gwami</span>
            <div class="card-twitter-icon">
              <a href="https://twitter.com/HighOnCryptoGuy">
                <TwitterBird />
              </a>
            </div>
          </div>
        </div>
        <div class="card col">
          <div class="card-body">
            <img
              class="card-img-top"
              src="../assets/PageThree/Lell.svg"
              alt="image-photo"
            />
            <h5 class="card-title">Lell</h5>
            <span>Creative director for Gwami</span>
            <div class="card-twitter-icon">
              <a href="https://twitter.com/Lelldesigns">
                <TwitterBird />
              </a>
            </div>
          </div>
        </div>
        <div class="card col">
          <div class="card-body">
            <img
              class="card-img-top"
              src="../assets/PageThree/Sy-Zygy.svg"
              alt="image-photo"
            />
            <h5 class="card-title">Sy Zygy</h5>
            <span>Advisor to GwamiLabs, product lead of KlimaDAO</span>
            <div class="card-twitter-icon">
              <a href="https://twitter.com/sy_zygy_">
                <TwitterBird />
              </a>
            </div>
          </div>
        </div>
      </div>
      <div class="d-none d-lg-block leaves-right">
        <img class="img-fluid" src="../assets/PageThree/Right-Leaf.svg" />
      </div>
      <div class="d-block d-lg-none leaves-bottom">
        <img class="img-fluid" src="../assets/PageThree/Bottom-Leaf.svg" />
      </div>
    </div>
  </section>
</template>

<script>
import TwitterBird from "./icons/TwitterBird.vue";
//import TeamMemberCard from "./TeamMemberCard.vue";
export default {
  name: "OurTeam",
  components: { TwitterBird },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.team-page-title {
  color: #202832;
  padding-top: 70px;
  font-size: 36px;
  z-index: 2;
}

.card {
  margin: 32px; /* Added */
  float: center;
  margin-top: 71px;
  min-height: 210px;
  min-width: 260px;
  width: 260px;
  background-color: #fcfff8;
  border: 2px solid #e6f6c7;
}

.card-img-top {
  height: 37.6%;
  position: absolute;
  top: -18.8%;
  right: 0.5%;
  left: 0.5%;
}

.card-title {
  margin-top: 43px;
  font-family: "Frank Ruhl Libre", serif;
  font-weight: 700;
  font-size: 20px;
}

.card-body {
  text-align: center;
  font-family: "OpenSans", sans-serif;
  font-weight: 400;
  font-size: 16px;
}

.card-twitter-icon {
  margin-top: 12px;
  padding-bottom: 6px;
}

.team-cards-holder {
  position: relative;
  padding-left: 115px;
  padding-right: 115px;
  padding-bottom: 140px;
  max-width: 1500px;
  z-index: 2;
}

.leaves-left {
  position: absolute;
  top: -120px;
  left: 2px;
  z-index: -1;
  height: 278px;
  width: 246px;
}

.leaves-right {
  position: absolute;
  bottom: 85px;
  right: 10px;
  z-index: -1;
  height: 263px;
  width: 203px;
}

.leaves-bottom {
  margin-left: 250px;
  margin-right: 250px;
  height: 263px;
  width: 203px;
}

@media only screen and (max-width: 767px) {
  .card {
    height: 260px;
  }

  .leaves-bottom {
    margin: auto;
  }
}
</style>
