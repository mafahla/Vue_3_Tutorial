<template>
  <div class="h-100">
    <div class="container-fluid h-100">
      <div class="row h-100">
        <div class="col-md-3 vue-bg d-flex justify-content-center align-items-center h-100">
           <img src="./assets/logo.png" alt="">
          </div>
          <div class="col-md-9 h-100">
              <SignUpForm />
          </div>
      </div>
    </div>

</div>
</template>

<script>
import SignUpForm from './components/SignUpForm.vue';

export default {
  name: 'App',
  components: {
   SignUpForm
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
body{
  margin: 0;
  background: #eee;
}
</style>
