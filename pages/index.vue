<!-- prettier-ignore -->
<template>
  <main class="h-full w-full bg-special text-white z-50">
    <div class="max-w-screen-xl mx-auto">
      <div class="py-8 md:py-12 flex justify-center">
        <img src="~/assets/logo-2-white.png" class="z-50" />
      </div>
      <div class="w-full flex flex-wrap px-12 flex-col md:flex-row justify-center items-center md:py-14 mb-4 ">
        <!-- center -->
        <div class="w-4/5 flex flex-col justify-center md:justify-start relative items-center md:items-stretch order-2">
          <h3 class="coming-soon-radius">Our website in under construction</h3>
          <h1 class=" text-2xl md:text-4xl mb-4 font-light text-center md:text-left">Our platform is launching soon</h1>
          <p class="text-base coming-soon-paragraph mb-12 text-center md:text-left px-2 md:px-0">ATLAS is a market intelligence (MARKINT) SaaS platform tool used for determining, predicting, and analyzing financial markets. </p>
          <div class="py-4"> 
            <CountdownTimer />
          </div>
          <Form />
        </div>
      </div>
      <!-- Footer -->
      <Footer />
    </div>
  </main>
</template>

<!-- eslint-disable -->
<script>

</script>
