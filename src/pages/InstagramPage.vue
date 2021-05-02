<template>
  <div class="instagram-page container-fluid">
    <div class="bg-top card main-card">
      <div class="row justify-content-center">
        <div class="col pt-3 text-center">
          <i class="text-white t-shadow fab fa-instagram fa-6x"></i>
        </div>
      </div>
      <div class="row justify-content-center">
        <div class="col text-white text-center">
          <h2 class="t-shadow">
            Instagram
          </h2>
        </div>
      </div>
      <div class="row justify-content-center">
        <div class="col text-white text-center">
          <p class="t-shadow mb-0">
            Purchase Followers, Likes, Comments, and Auto Likes!
          </p>
          <p class="t-shadow pb-3">
            Pick a package and start creating more <em class="text-dark"><b class="b-shadow">BUZZ!</b></em>
          </p>
        </div>
      </div>
    </div>
    <div class="row mt-3 justify-content-center">
      <div class="col-3">
        <div class="card  text-center">
          <h4 class="mt-2 mb-0">
            BUY
          </h4>
          <h5 class="mb-3">
            <b>200 followers</b>
          </h5>
          <h2><b>$4.99</b></h2>
          <button class="btn btn-dark m-1">
            Purchase
          </button>
          <p class="m-1">
            <em><small>Recieve in 7 business days</small></em>
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>

export default {
  components: {},
  name: 'InstagramPage'
}
</script>

<style>
.bg-top{
  background-image:linear-gradient(45deg, #405de6, #5851db, #833ab4, #c13063, #fd1d1d)
}
.t-shadow{
  text-shadow: 2px 4px 10px rgb(37, 37, 37)
}
.b-shadow{
  text-shadow: -4px 2px 10px #a4358a;
}
.main-card{
  border: transparent;
  border-radius: 15px;
}
.card{
  border-radius: 15px;
}
</style>
