<script setup>
definePageMeta({
  layout: "landing",
});
</script>

<template>
  <div class="bg-[url('~/assets/img/heroimg.jpg')] bg-black bg-opacity-75 bg-cover bg-center bg-blend-darken h-[600px] relative">
    <div class="absolute inset-0 opacity-50"></div>
    <main class="absolute inset-0 p-4 md:p-24 flex flex-col justify-center text-white">
      <div class="max-w-xl md:ml-20">
        <div class="md:text-left">
          <h1 class="text-4xl md:text-4xl lg:text-5xl xl:text-5xl font-bold lg:tracking-tight">
            We have been helping brands craft value driven content for their audiences since 2020
          </h1>
          <div class="mt-6 flex flex-col sm:flex-row gap-3 md:gap-0">
            
          </div>
        </div>
      </div>
    </main>
  </div>
  <LandingContainer>
    <div class="md:text-left mt-8 mb-8 md:mb-0 md:w-1/2 md:block">
      <h6 class="text-red-600 font-bold">About Company</h6>
      <span class="text-red-600">&rarr;</span>
      <h1 class="text-3xl md:text-3xl lg:text-4xl xl:text-5xl font-bold l:tracking-normal">
        Ardasha <wbr/><span class="text-red-600 md:inline">Designs</span>
      </h1>
      <p class="mt-4 mb-6">Ardasha Designs is an African based digital content and creative agency in Africa, focused on helping brands build authentic, meaningful narratives in the digital space. 
        We partner with brands and individuals to create delightful and enjoyable customer experiences.
        We bring together a balanced blend of creative minds & digital thinkers backed up by a well informed processes in innovation and problem solving.
      </p>
    </div>

    <div>
      <h1 class="text-3xl md:text-3xl lg:text-3xl xl:text-4xl font-bold l:tracking-normal">
        Our Promise
      </h1>
    </div>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-4 mt-8 mb-8">
      <!-- Card 1 -->
      <div class="bg-gray-200 p-6">
        <div class="flex items-center justify-center w-12 h-12  text-black mb-4">
          <Icon class="h-8 md:h-12" name="simple-icons:vercel" size="48" />
        </div>
        <h3 class="text-xl font-semibold text-gray-800 mb-2">Expert Guidance</h3>
        <p class="text-black">
          Get valuable insights and personalized recommendations every step of the way from design and branding professionals with years of experience.
        </p>
      </div>

      <!-- Card 2 -->
      <div class="bg-gray-200 p-6">
        <div class="flex items-center justify-center w-12 h-12  text-black mb-4">
          <Icon class="h-8 md:h-12" name="simple-icons:vercel" size="48" />
        </div>
        <h3 class="text-xl font-semibold text-gray-800 mb-2">Efficiency</h3>
        <p class="text-black">
          Expect clear communication and seamless execution from kickoff to completion, guaranteeing project delivery right on the dot without compromised quality.
        </p>
      </div>

      <!-- Card 3 -->
      <div class="bg-gray-200 p-6">
        <div class="flex items-center justify-center w-12 h-12  text-black mb-4">
          <Icon class="h-8 md:h-12" name="simple-icons:vercel" size="48" />
        </div>
        <h3 class="text-xl font-semibold text-gray-800 mb-2">Partnership</h3>
        <p class="text-black">
          Enjoy true collaboration. We work closely with you, using your input and industry knowledge as a springboard to achieve shared goals and exceed expectations.
        </p>
      </div>
    </div>
  </LandingContainer>
  <landingContainer>
    <LandingLogos></LandingLogos>
  </landingContainer>
</template>
