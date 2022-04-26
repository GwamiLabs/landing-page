<template>
  <section id="Intro" class="intro-Page" style="background-color:#F3FCE2;">
    <NavBar/>
    <div class="row justify-contents-between">
      <div class="d-flex flex-column flex-lg-row">
      <div class="d-none d-lg-block col-3">
        <img class="" src="../assets/PageOne/Leaves-Pg1-Left.svg"/>
      </div>
      <div class="d-block d-lg-none col-12">
        <img class="col-12 img-fluid" src="../assets/PageOne/Leaves-Pg1-Top.svg"/>
      </div>
      <div class="col-12 col-lg-6 py-0 py-lg-1 text-center">
        <h1 class="intro-title">
          Products for climate action
        </h1>
        <p class="intro-body">
        Gwami Labs is focused on building a suite of blockchain 
        and web2 based products on the refi ecosytem. 
        The goal is to make Climate Action the only option 
        through accessibility, incentives, social culture, 
        education and amplification.</p>
        <div>
        <span class="PageOneLegend">Unlock Refi</span>
        <br class="d-block d-lg-none">
        <span class=" mx-3 PageOneLeafIcon">
          <img src="../assets/PageOne/Green-Leaf-2.svg"/>
        </span>
        <br class="d-block d-lg-none">
        <span class="PageOneLegend">Build on KlimaDAO</span>
        <br class="d-block d-lg-none">
        <br class="d-none d-lg-block">
        <span class="d-block d-lg-none PageOneLeafIcon">
          <img src="../assets/PageOne/Green-Leaf-2.svg"/>
        </span>
        <br class="d-block d-lg-none">
        <span class="PageOneLegend">Collaborate globally</span>
        <br class="d-block d-lg-none">
        <span class=" mx-3 PageOneLeafIcon">
          <img src="../assets/PageOne/Green-Leaf-2.svg"/>
        </span>
        <br class="d-block d-lg-none">
        <span class="PageOneLegend">Promote climate action</span>
        <br class="d-block d-lg-none">
        <br class="d-block d-lg-none">
        </div>
      </div>
      <div class="d-none d-lg-block col-3">
        <img class="img-fluid" src="../assets/PageOne/Leaves-Pg1-Right.svg"/>
      </div>
       <div class="d-block d-lg-none col-12">
        <img class="col-12 img-fluid" src="../assets/PageOne/Leaves-Pg1-Bottom.svg"/>
      </div>
    </div>
    </div>
  </section>
</template>

<script>
import NavBar from "./NavBar.vue";
export default {
    name: "CardOne",
    components: { NavBar }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

p {
    color:#304010;
    margin-top:51px;
    font-size:20px;
}

h1, h2, h3, h4, h5, h6
{
    color:#304010;
}

h1 {
  margin-top:17.6%;
  font-size:72px;
}

.PageOneLegend{
    font-family: 'Frank Ruhl Libre', serif;
    font-weight: 700;
    font-size :24px;
    color:#304010;
}


.leaves-bottom{
  transform: scale(1,1);

}

.leaves-top{
  transform: scale(1,1);
}

@media only screen and (max-width: 992px and min-width:768px) {

  h1 {
    margin-top:20px;
    font-size:44px;
  }
  p {
    margin-top:10px;
    font-size:22px;
  }
  .PageOneLegend {
    font-size:24px;
    white-space: nowrap;
    margin-top:8px;
    margin-bottom:8px;
  }

.leaves-bottom{
  transform: scale(7,1);

}

.leaves-top{
  transform: scale(7,1);
}

}

@media only screen and (max-width: 767px and min-width:577px) {

  h1 {
    margin-top:25px;
    font-size:40px;
  }
  p {
    font-size:20px;
  }
  .PageOneLegend {
    font-size:22px;
    white-space: nowrap;
  }

.leaves-bottom{
  transform: scale(3,1);

}

.leaves-top{
  transform: scale(3,1);
}

}

@media only screen and (max-width: 576px) {

  h1 {
    margin-top:15px;
    font-size:36px;
  }
  p {
    margin-top: 15px;
    font-size:18px;
  }
  .PageOneLegend {
    font-size:20px;
    white-space: nowrap;
    text-align: left;
  }

  .leaves-bottom{
  transform: scale(1.5,1);

}

.leaves-top{
  transform: scale(1.5,1);
}

}


</style>
