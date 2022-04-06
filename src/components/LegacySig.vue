<template>
<div class="col">
    <div class="card mb-5" style="width: 18rem;">
        <div class="card-body">
        <h5 class="card-title">{{sigName}}</h5>
        <h6 class="card-subtitle mb-2 text-muted">{{year}}</h6>
        <h6 class="card-subtitle mb-2 text-muted">{{leader}}</h6>
        </div>
    </div>
</div>
</template>

<script>
  export default {
    props:{
        leader: String,
        year: String,
        sigName: String
    }
  }
</script>