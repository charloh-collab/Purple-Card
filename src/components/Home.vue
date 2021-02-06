<template>
  <div class="container-fluid m-0 p-0">
    <div id="home-page" class="full-height p-4">
      <div class="row pb-5">
        <div class="col-lg-6 my-auto pt-4">
          <div class="text-center mb-3 d-none d-lg-block">
            <h1 class="display-3">{{ title }}</h1>
            <h3>We feel like an aliens sometimes, where we don't feel like we belong anywhere.</h3>
                <button type="submit" class="btn rounded btn-success mt-3 home-button">
                  Join the Revolution
                </button>
          </div>

          <!-- <div class="border p-3 p-md-5 bg-white rounded shadow">
            <h2>Coming Soon</h2>
            <form>
              <div class="form-group">
                <label for="emailSignup">Reserve your account now!</label>
                <input
                  id="emailSignup"
                  placeholder="Enter Email Address"
                  class="form-control"
                />
                <small id="emailHelp" class="form-text text-muted"
                  >We would never share your email address!</small
                >
                <button type="submit" class="btn btn-success mt-3">
                  Join Waiting List
                </button>
              </div>
            </form>
          </div> -->

          <div id="available" class="p-2">
            <!-- <h4 class="text-center mb-2 mt-2 mt-3 text-dark">
              Available on Stores
            </h4> -->
            <!-- <div class="row">
              <div class="col my-auto">
                <img src="../assets/app-store.png" class="float-right img-fluid app-store-img"/>
              </div>
              <div class="col my-auto">
                <img src="../assets/play-store.png" class="float-left img-fluid app-store-img" />
              </div>
            </div> -->
          </div>
        </div>
        <div class="col-lg-6 p-4 my-auto">
          <div class="text-center mb-3 d-block d-lg-none">
            <h1 class="display-3 main-title">{{ title }}</h1>
            <h3>Make Payment Easy</h3>
          </div>
          <img src="../assets/Laptop-reply.png" id="phone" />
        </div>
      </div>
    </div>
    <div id="about" class="bg-light p-3 p-md-5">
      <div class="row">
        <div class="col-lg">
          <img src="../assets/fonts/Comments.png" class="image-icon" alt="icons">
          <h5 class="ml-md-4 mr-md-4">
            Already know HTML, CSS and JavaScript? Read the guide and start building things in no time!
          </h5>
        </div>
         <div class="col-lg">
          <img src="../assets/fonts/Grow.png" class="image-icon" alt="icons">
         <h5 class="ml-md-4 mr-md-4">
            Already know HTML, CSS and JavaScript? Read the guide and start building things in no time!
          </h5>
        </div>
         <div class="col-lg">
          <img src="../assets/fonts/Message.png" class="image-icon" alt="icons">
         <h5 class="ml-md-4 mr-md-4">
            Already know HTML, CSS and JavaScript? Read the guide and start building things in no time!
          </h5>
        </div>
      </div>
    </div>
    <div id="contact" class="bg-info p-4"></div>
    <div id="footer" class="bg-primary p-4"></div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      title: "We are not Aliens"
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Fredoka+One&family=Roboto&display=swap');
#home-page {
  background-color: #fff;
  background: url("../assets/bg.png") no-repeat center center;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
  
}
.h1, .h2, .h3, .h4, .h5, .h6, h1, h2, h3, h4, h5, h6 {
    margin-bottom: .5rem;
    font-weight: 500;
    line-height: 1.2;
    font-family: 'Roboto', sans-serif; 
}
.main-title{
   font-family: 'Fredoka One', cursive ;
   src: url('../fonts/FredokaOne-Regular.ttf');
}
.display-3 {
    font-size: 4.5rem;
    font-weight: 300;
    line-height: 1.2;
    font-family: 'Fredoka One', cursive;

}
.btn-success {
    color: #fff;
    background-color: #2A62C6;
    border-color: #2A62C6;
    height: 60px;
    width: 250px;
    border-radius: 50px !important;
    font-family: 'Roboto', sans-serif; 
    font-weight: 500;
}
.btn-success:hover {
    color: #fff;
    background-color: #6681FA;
    border-color: #6681FA;
    height: 60px;
    width: 250px;
    border-radius: 50px !important;
    font-family: 'Roboto', sans-serif; 
    font-weight: 500;
}
.image-icon{
  width: 128px;
  height: 128px;
}
#phone {
  max-height: 85vh;
}
#about{
 height:  40vh;
}
.app-store-img{
  max-height: 80px;
}
</style>
