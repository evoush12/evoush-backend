<template>
  <div>
    <div id="hero-home">
      <div class="jumbotron jumbotron-fluid jumbotron-content" :style="image">
        <div class="container">
          <div class="row no-gutters justify-content-center">
            <div class="col-md-6 col-xs-12 col-sm-12">
              
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  export default{
    data(){
      return {
        image: {
          backgroundImage: `url(https://raw.githubusercontent.com/codesyariah122/bahan-evoush/main/images/MARKETING%20PLAN/1.jpg)`
        }
      }
    }
  }
</script>

<style scoped>
.jumbotron-content {
  text-align: center;
  position: relative;
  background-color: #17234E;
  margin-bottom: 0;
  /*background-repeat: no-repeat;
  -webkit-background-size: cover;
  background-size: cover;*/
  background-position: center;
  background-size: contain;
  min-height: 100vh;
  height: 100vh;
  width: 100%;
  position: relative;
  clip-path: polygon(50% 0%, 100% 0, 100% 89%, 92% 92%, 84% 94%, 50% 100%, 0 100%, 0 59%, 0 0);
  z-index: -1!important;
}

.jumbotron-content .container {
  z-index: 1;
  position: relative;
  margin-top: -1.5rem!important;
}

.jumbotron-content::after {
  content: "";
  display: block;
  width: 100%;
  height: 100%;
  background-image: linear-gradient(to top, rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0));
  position: absolute;
  bottom: 0;
}

.jumbotron-content .display-4 {
  color: white;
  text-align: center;
  margin-top: 9rem;
  font-weight: 200;
  text-shadow: 1px 1px 1px rgba(0, 0, 0, 0.5);
  margin-bottom: 10px!important;
  font-family: "Poppins", sans-serif;
}

.jumbotron-content .display-4 span {
  font-weight: 500;
  color: tomato;
}

.jumbotron-content p {
  font-weight: 500;
  font-size: 21px;
  color: #FFFFF0;
  font-family: "Poiret One", cursive;
  font-weight: bold;
}

@media (min-width: 992px) { 
  .jumbotron-content{
    margin-top: -75px;
    height: 840px;
    z-index: -1!important;
    min-height: 100vh;
    width: 100%;
    -webkit-background-size: cover;
    background-size: cover;
    position: relative;
    clip-path: polygon(50% 0%, 100% 0, 100% 89%, 92% 92%, 84% 94%, 50% 100%, 0 100%, 0 59%, 0 0);
  }
  .jumbotron-content .container{
    margin-top: 3rem!important;
  }
  .jumbotron-content .display-4{
    text-transform: capitalize;
  }
  .jumbotron-content p{
    font-size: 31px!important;
  }
}
</style>