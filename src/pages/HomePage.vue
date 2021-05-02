<template>
  <div class="home container-fluid">
    <div class="row bg-top justify-content-center">
      <div class="col-6 mt-5 text-white text-center">
        <h1 class="t-shadow">
          Want to be a social media influencer?
        </h1>
      </div>
    </div>
    <div class="row pb-5 bg-top justify-content-center">
      <div class="col-8 text-center text-white">
        <p class="m-0 t-shadow">
          We're here to help you get the <em class="text-dark"><b class="b-shadow">BUZZ</b></em> you've always deserved!
        </p>
        <p class="m-0 t-shadow">
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
        <div class="card pb-3 hiw-card">
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
              <p>The best prices to get the most out for your dollar!</p>
            </div>
            <div class="col-4 mt-2 text-center">
              <p>Account <em><b>MUST be PUBLIC</b></em> to recieve followers!</p>
            </div>
            <div class="col-4 mt-2 text-center">
              <p>Youre financial information is never stored.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="row my-3">
      <div class="col text-center">
        <h1>Social Media</h1>
      </div>
    </div>
    <div class="row">
      <div class="col-3">
        <div class="card scard p-1 text-center img-fluid">
          <img src="../assets/img/insta.png" alt="">
        </div>
      </div>
      <div class="col-3">
        <div class="card scard p-1 text-center img-fluid">
          <img src="../assets/img/fbook.png" alt="">
        </div>
      </div>
      <div class="col-3">
        <div class="card scard p-1 text-center img-fluid">
          <img src="../assets/img/tiktoklogo.png" alt="">
        </div>
      </div>
      <div class="col-3">
        <div class="card scard p-1 text-center img-fluid">
          <img src="../assets/img/yt.png" alt="">
        </div>
      </div>
    </div>
    <div class="row">
      <div class="col-3">
        <div class="card scard p-1 mt-2 text-center img-fluid">
          <!-- <i class="fab fa-tiktok fa-8x" id="tiktok"></i> -->
          <img src="../assets/img/twitter.png" alt="">
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
.t-shadow{
  text-shadow: 3px 6px 10px rgb(37, 37, 37)
}
.b-shadow{
  text-shadow: -4px 2px 10px rgb(170, 22, 22);
}
.hiw-card{
  box-shadow: 3px 8px 12px rgb(153, 152, 152);
  background-image: linear-gradient(180deg, rgb(255, 255, 255), rgb(197, 197, 197));
  border: none;

}

.step{
text-decoration: underline red;
margin-top: 5%;
}

.scard{
  border-radius: 10%;
  background-image: linear-gradient(720deg, rgb(255, 255, 255), rgb(197, 197, 197));
  box-shadow: 3px 8px 12px rgb(153, 152, 152);
}

</style>
