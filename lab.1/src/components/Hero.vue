<template>
<div class="bg-light">
  <div class="container py-5 z-depth-1 text-center text-lg-left bg-white">


    <!--Section: Content-->
    <section class="px-md-5 mx-md-5 dark-grey-text">

      <!--Grid row-->
      <div class="row">

        <!--Grid column-->
        <div class="col-lg-6 mb-4">

          <img src="https://mdbootstrap.com/wp-content/uploads/2018/06/logo-mdb-jquery-small.png" class="img-fluid mb-5"
            alt="">

          <h3 class="font-weight-bold">{{ msg }}</h3>

          <a v-on:click="btnFunction" class="btn btn-secondary btn-md ml-0" href="#" role="button">Click me!</a>

        </div>
        <!--Grid column-->

        <!--Grid column-->
        <div class="col-lg-6 mb-4">

          <!--Image-->
          <div class="view overlay z-depth-1-half">
            <img src="https://mdbootstrap.com/img/Photos/Others/img%20(27).jpg" class="img-fluid"
              alt="">
            <a href="#">
              <div class="mask rgba-white-light"></div>
            </a>
          </div>

        </div>
        <!--Grid column-->

      </div>
      <!--Grid row-->


    </section>
    <!--Section: Content-->


  </div>
  </div>
</template>

<script>
export default {
    data() {
        return {
            msg: 'Before click!' 
        }
    },
    methods: {
        btnFunction() {
            console.log('You clicked on CLICK ME! button')
            this.msg= 'After click!'
        }
    }
}
</script>

<style>

</style>