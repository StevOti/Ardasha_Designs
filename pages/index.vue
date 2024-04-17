<script setup>
definePageMeta({
  layout: "landing",
});
</script>

<template>
  <div class="mb-16">
    <LandingHero></LandingHero>
  </div>
  <LandingContainer>
    <LandingFeatures></LandingFeatures>
    <!-- <LandingLogos></LandingLogos> -->
    <!-- <LandingCta></LandingCta> -->
  </LandingContainer>

  <div class="mt-16 mb-16">
    <LandingSolutions></LandingSolutions>
  </div>
  
  <LandingContainer class="mt-16 mb-16">
    <LandingPortfolio></LandingPortfolio>
  </LandingContainer>
</template>
