<template>
  <div id="card">
    <b-card-body>
      <div class="circular" v-bind:style="{ 'background-image': 'url(  )' }">
        <p id="p">"Value everyone's comfort in the world of travel"</p>
        <button id="btn">Learn more</button>
      </div>
    </b-card-body>
  </div>
</template>
<style>
#p {
  font-size: 80px;
  margin-top: 10%;
  margin-left: 8%;
  text-align: center;
}
#btn {
  background-color: green;
  margin-left: 45%;
  color: white;
  padding-left: 2%;
  padding-right: 2%;
  padding-top: 1%;
  padding-bottom: 1%;
}
div {
  /* background:url(https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSvn1vhmcUVSTg3nxpYw6rfKXaApuXrjSnv4t62ozKeet_xUaceoQ&s);*/
  background-repeat: no-repeat;
  position: cover;
}
</style>