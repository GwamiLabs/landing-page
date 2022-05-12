<template>
  <section
    id="Products"
    class="PageTwo"
    style="
      background-color: #485f1d;
      text-align: center;
      max-width: 1440px;
      margin: auto;
    "
  >
    <div class="container">
      <h1 class="product-page-title">
        <span class="text-dash-icon">
          <img src="../assets/PageTwo/Text-framer-emdash.svg" />
        </span>
        Our Products
        <span class="text-dash-icon">
          <img src="../assets/PageTwo/Text-framer-emdash.svg" />
        </span>
      </h1>
      <div class="container-fluid">
        <div class="row">
          <div
            class="col-12 col-lg-6 g-5 text-align-start justify-contents-start"
          >
            <h1 class="block-titles">KlimaDAO Name Service (KNS)</h1>
            <p>
              KlimaDAO Name Service (KNS) is the world’s first regenerative
              domain that continuously offsets your carbon footprint and
              socially represents your carbon neutrality. KNS also enables users
              to map human readable names to blockchain and non-blockchain
              resources, like Ethereum addresses, IPFS hashes, or website URLs.
            </p>
            <button class="kns-button">
              <a href="https://www.kns.earth"> View KNS </a>
            </button>
          </div>
          <div class="col-12 col-lg-6 g-5 d-flex align-top">
            <img
              class="d-none d-md-block img-fluid mb-5"
              src="../assets/PageTwo/SampleKlimaDomains.svg"
            />
            <img
              class="d-block d-md-none img-fluid mb-5"
              src="../assets/PageTwo/SampleKlimaDomains.png"
            />
            <div style="margin-bottom: 96px"><br /></div>
          </div>
        </div>
        <div class="row" style="padding-bottom: 100px">
          <div
            class="col-12 col-lg-6 g-3 d-flex flex-column text-start bg-transparent"
          >
            <h1 class="block-titles">TerraNeutral Platform</h1>
            <div>
              <p>
                A social platform for Refi, suitable for both individuals and
                businesses
              </p>
            </div>
          </div>
          <div
            class="col-12 col-lg-6 g-3 d-flex flex-column align-items-center product-page-title"
          >
            <h1 class="coming-soon">Coming Soon</h1>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "OurProducts",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
a {
  text-decoration: none;
  color: inherit;
  font-size: inherit;
  font-weight: inherit;
}

p {
  color: #fcfff8;
  margin-top: 51px;
  font-size: 20px;
  text-align: left;
}

h1,
h2,
h3,
h4,
h5,
h6 {
  color: #fcfff8;
}

.kns-button {
  float: left;
  border-radius: 2px;
  border: 1px solid #cee899;
  font-weight: bold;
  font-size: 16px;
  height: 54px;
  width: 148px;
  color: #485f1d;
  background: #cee899;
  margin-bottom: 96px;
  margin-top: 20px;
}

.product-page-title {
  color: #fcfff8;
  padding-top: 70px;
  font-size: 36px;
}

.block-titles {
  font-size: 60px;
  overflow-wrap: normal;
  text-align: left;
}

.card {
  border: 1px;
}

.coming-soon {
  padding-left: 120px;
}

@media only screen and (max-width: 992px and min-width:768px) {
  .coming-soon {
    padding-left: 10px;
  }

  .block-titles {
    font-size: 50px;
    overflow-wrap: normal;
  }

  .product-page-title {
    padding-top: 125px;
    padding-bottom: 90px;
    font-size: 30px;
  }

  .kns-button {
    margin-bottom: 50px;
  }
}

@media only screen and (max-width: 767px and min-width:577px) {
  .coming-soon {
    padding-left: 10px;
  }

  .block-titles {
    font-size: 34px;
    overflow-wrap: normal;
  }

  .product-page-title {
    padding-top: 25px;
    font-size: 25px;
  }

  .kns-button {
    margin-bottom: 40px;
  }
}

@media only screen and (max-width: 576px) {
  .coming-soon {
    padding-left: 10px;
  }

  .block-titles {
    font-size: 30px;
    overflow-wrap: normal;
  }

  .product-page-title {
    padding-top: 96px;
    font-size: 20px;
  }

  .kns-button {
    margin-bottom: 35px;
  }
}
</style>
