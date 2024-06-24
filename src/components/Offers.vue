<template>
   <section :class="isDark ? 'bg-dark':'bg-yellow'">
    <div class="container py-4 p-lg-5">
      <h2 :class="isDark ? 'text-yellow':''" class="display-5 text-center mb-4 my-b-1">{{title}}</h2>
      <div class="row text-white">
        <div class="col-6 col-xl-3 d-flex justify-content-center mb-4">
          <div class="card bg-transparent" style="width: 15rem;">
          <img class="card-img-top" src="/hpelitebook.jpeg" alt="Title" />
          <div class="card-body border-light">
            <h4 :class="isDark ? 'text-yellow':''" class="card-title">hp elite book.</h4>
            <p :class="isDark ? 'text-yellow':''" class="card-text text-start mb-2">laptop</p>
            <span :class="isDark ? 'text-yellow':''" class="d-block fw-bold mb-2">$800</span>
            <div class="d-flex">
              <button :class="isDark ? 'btn btn-light':'btn btn-dark'" class="btn-sm me-2">
                Buy Now
              </button>
              <button class="btn btn-sm" :class="isDark ? 'btn-outline-light':'btn-outline-dark'" >
                Add to cart
              </button>
            </div>
          </div>
        </div>
        </div>  
        <div class="col-6 col-xl-3 d-flex justify-content-center mb-4">
          <div class="card bg-transparent" style="width: 15rem;">
          <img class="card-img-top" src="/iphone12png.jpeg" alt="Title" />
          <div class="card-body border-light">
            <h4 :class="isDark ? 'text-yellow':''" class="card-title">iphone12.</h4>
            <p :class="isDark ? 'text-yellow':''" class="card-text text-start mb-2">phone</p>
            <span :class="isDark ? 'text-yellow':''" class="d-block fw-bold mb-2">$1000</span>
            <div class="d-flex">
              <button :class="isDark ? 'btn btn-light':'btn btn-dark'" class="btn-sm me-2">
                Buy Now
              </button>
              <button class="btn btn-sm" :class="isDark ? 'btn-outline-light':'btn-outline-dark'" >
                Add to cart
              </button>
            </div>
          </div>
        </div>
        </div>  
        <div class="col-6 col-xl-3 d-flex justify-content-center mb-4">
          <div class="card bg-transparent" style="width: 15rem;">
          <img class="card-img-top" src="/iphonexr.jpeg" alt="Title" />
          <div class="card-body border-light">
            <h4 :class="isDark ? 'text-yellow':''" class="card-title">iphone-xr.</h4>
            <p :class="isDark ? 'text-yellow':''" class="card-text text-start mb-2">phone</p>
            <span :class="isDark ? 'text-yellow':''" class="d-block fw-bold mb-2">$500</span>
            <div class="d-flex">
              <button :class="isDark ? 'btn btn-light':'btn btn-dark'" class="btn-sm me-2">
                Buy Now
              </button>
              <button class="btn btn-sm" :class="isDark ? 'btn-outline-light':'btn-outline-dark'" >
                Add to cart
              </button>
            </div>
          </div>
        </div>
        </div>  
        <div class="col-6 col-xl-3 d-flex justify-content-center mb-4">
          <div class="card bg-transparent" style="width: 15rem;">
          <img class="card-img-top" src="/axuslap.jpeg" alt="Title" />
          <div class="card-body border-light">
            <h4 :class="isDark ? 'text-yellow':''" class="card-title">axus.</h4>
            <p :class="isDark ? 'text-yellow':''" class="card-text text-start mb-2">Laptop</p>
            <span :class="isDark ? 'text-yellow':''" class="d-block fw-bold mb-2">$1200</span>
            <div class="d-flex">
              <button :class="isDark ? 'btn btn-light':'btn btn-dark'" class="btn-sm me-2">
                Buy Now
              </button>
              <button class="btn btn-sm" :class="isDark ? 'btn-outline-light':'btn-outline-dark'" >
                Add to cart
              </button>
            </div>
          </div>
        </div>
        </div>  
      </div>
    </div>
  </section>
</template>

<script setup>
const props = defineProps({
    title: String,
    isDark: Boolean
})
</script>

<style>

</style>