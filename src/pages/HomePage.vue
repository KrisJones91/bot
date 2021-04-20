<template>
  <div class="home container-fluid">
    <div class="row bg-top justify-content-center">
      <div class="col-6 mt-5 text-white text-center">
        <h1>Want to be a social media influencer?</h1>
      </div>
    </div>
    <div class="row pb-5 bg-top justify-content-center">
      <div class="col-8 text-center text-white">
        <p class="m-0">
          We're here to help you get the <em class="text-dark"><b>BUZZ</b></em> you've always deserved!
        </p>
        <p class="m-0">
          <small>Purchase followers, likes, and views in 3 simple steps!</small>
        </p>
        <!-- <p>Let <b>Social Buzz</b> help you get the <em class="text-danger">buzz</em> you've always deserved!</p>
      </div> -->
      </div>
    </div>
    <div class="row justify-content-center">
      <div class="col">
        <h1 class="m-3 text-center">
          How it works:
        </h1>
        <div class="card hiw-card">
          <div class="row justify-content-center">
            <div class="col box1 text-center">
              <h1 class="step">
                Step 1
              </h1>
              <p class="ml-2">
                Choose a package
              </p>
            </div>
            <div class="col box2 text-center">
              <h1 class="step">
                Step 2
              </h1>
              <p class="mb-0">
                Provide your username
              </p>
              <p class="mt-0">
                <small><b class="text-danger">NO PASSWORD REQUIRED</b></small>
              </p>
            </div>
            <div class="col box3 text-center">
              <h1 class="step">
                Step 3
              </h1>
              <p>Checkout!</p>
            </div>
          </div>
          <div class="row justify-content-center">
            <div class="col-3 text-center">
              <i class="fas fa-box-open fa-4x"></i>
            </div>
            <div class="col-1 text-center">
              <i class="fas fa-angle-double-right fa-2x"></i>
            </div>
            <div class="col-3 text-center">
              <i class="far fa-user fa-4x"></i>
            </div>
            <div class="col-1 text-center">
              <i class="fas fa-angle-double-right fa-2x"></i>
            </div>
            <div class="col-3 text-center">
              <i class="far fa-credit-card fa-4x"></i>
            </div>
          </div>
          <div class="row">
            <div class="col-4 mt-2 text-center">
              <p>The best prices to get the most out of your buck!</p>
            </div>
            <div class="col-4 mt-2 text-center">
              <p>Account <em><b>MUST be PUBLIC</b></em> to recieve followers!</p>
            </div>
            <div class="col-4 mt-2 text-center">
              <p>Our secure  Youre financial information is never stored!</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Home'
}
</script>

<style scoped lang="scss">
.bg-top{
  background-image: linear-gradient(to right,rgba(71, 15, 15), rgb(170, 22, 22), rgb(170, 22, 22), rgb(71, 15, 15));
}

.hiw-card{
  box-shadow: 3px 8px 12px rgb(153, 152, 152);
  background-color: rgb(255, 255, 255);
}

.step{
text-decoration: underline red;
margin-top: 5%;
}
</style>
