<script lang="ts">
  import Header from "$lib/components/Header.svelte";
  import Hero from "$lib/components/Hero.svelte";
  import ValueProp from "$lib/components/ValueProp.svelte";
  import Workflows from "$lib/components/Workflows.svelte";
  import TrustedData from "$lib/components/TrustedData.svelte";
  import AIFeatures from "$lib/components/AIFeatures.svelte";
  import Security from "$lib/components/Security.svelte";
  import Testimonial from "$lib/components/Testimonial.svelte";
  import Footer from "$lib/components/Footer.svelte";
</script>

<div class="bg-white">
  <Header />
  <main>
    <Hero />
    <ValueProp />
    <Workflows />
    <TrustedData />
    <AIFeatures />
    <Security />
    <Testimonial />
  </main>
  <Footer />
</div>

