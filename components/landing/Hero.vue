<template>
  <div class="bg-[url('~/assets/img/heroimg.jpg')] bg-black bg-opacity-75 bg-cover bg-center bg-blend-darken h-[600px] relative">
    <div class="absolute inset-0 opacity-50"></div>
    <main class="absolute inset-0 p-4 md:p-24 flex flex-col justify-center text-white">
      <div class="max-w-xl md:ml-20">
        <div class="md:text-left">
          <h1 class="text-3xl md:text-5xl lg:text-6xl xl:text-7xl font-bold lg:tracking-tight">
            Your Business Growth With Ardasha <span class="text-red-600">Designs</span>
          </h1>
          <div class="mt-6 flex flex-col sm:flex-row gap-3 md:gap-0">
            <LandingLink
              href="contact/"
              target="contact us"
              rel="noopener"
              class="md:inline-block"
              >Contact Us</LandingLink
            >
          </div>
        </div>
      </div>
    </main>
  </div>
</template>
