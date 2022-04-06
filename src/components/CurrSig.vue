<template>
<div>
      <div class="card-body row">
        <div class="col-4">
          <img class="w-100 d-block" :src="logo">
        </div>
        <div class="col-8" style="text-align: center;">
          <h3>{{sigTitle}}</h3>
          <h5>{{leader}} | {{leaderTime}}</h5>
          <p>{{sigDesc}}</p>
        </div>
      </div>
</div>
</template>
<script>
  export default {
    props:{
        sigTitle: String,
        sigDesc: String,
        leader: String,
        leaderTime: String,
        logo: String
    }
  }
</script>