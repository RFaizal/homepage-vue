<script setup></script>

<template>
  <section class="hero">
    <div class="container-fluid px-5 py-5">
      <div class="row flex-lg-row-reverse align-items-center g-5 py-5 order-lg-first">
        <div class="col-12 col-sm-8 col-lg-6 ms-10">
          <lottie-player
            src="https://assets1.lottiefiles.com/packages/lf20_aorkkcxr.json"
            class="mx-auto"
            background="transparent"
            speed="1"
            style="width: 400px; height: 400px"
            loop
            autoplay
          ></lottie-player>
        </div>
        <div class="col-lg-6">
          <h1 class="display-5 fw-bold lh-1 mb-3">Responsive left-aligned hero with image</h1>
          <p class="lead">
            Quickly design and customize responsive mobile-first sites with Bootstrap, the world’s
            most popular front-end open source toolkit, featuring Sass variables and mixins,
            responsive grid system, extensive prebuilt components, and powerful JavaScript plugins.
          </p>
          <div class="d-grid gap-2 d-md-flex justify-content-md-start">
            <button type="button" class="btn btn-primary btn-lg px-4 me-md-2">Primary</button>
            <button type="button" class="btn btn-outline-secondary btn-lg px-4">Default</button>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped></style>
