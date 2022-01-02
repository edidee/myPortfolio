<template>
  <div class="container-fluid">
    <div class="row">
    <div class="col-lg-6 first-col container ">
      <h1>Edidiong <br>
      Frontend Developer.</h1>
      <button type="button" class="btn btn-dark">Let's Talk</button>
    </div>
    <div class="col-lg-6">
      <img src="../assets/gif.gif" alt="">
    </div>
  </div>
    
  </div>
</template>

<script>
// @ is an alias to /src


export default {
  name: 'Home',
  components: {
    
  }
}
</script>

<style scoped>
.container-fluid{
  background-color: #FED964;
  padding-top: 2rem;
  height: 100%;
}

.first-col {
  text-align: left;
  padding-left: 1.0rem;
}

.first-col h1 {
  font-family: "Space Grotesk", sans-serif;
}

@media screen and (min-width: 480px) {
.first-col {
  padding-left: 3.4rem;
}
}
</style>
