<script setup lang="ts">
import CtaSection from "~/components/CtaSection.vue";
import FeaturesSection from "~/components/FeaturesSection.vue";
import HeroSection from "~/components/HeroSection.vue";

useHead({
  title: "Mi Landing Page Increible",
  meta: [
    {
      name: "description",
      content: "La mejor solucion para potenciar tu negocio con Nuxt.",
    },
  ],
});
</script>

<template>
  <div>
    <!-- <head>
      <title>Mi Landing Page Increible</title>
      <Meta
        name="description"
        content="La mejor solucion para potenciar tu negocio con Nuxt."
      />
    </head> -->
    <HeroSection />
    <FeaturesSection />
    <CtaSection />
  </div>
</template>
