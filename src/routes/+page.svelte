<script lang="ts">
  import Navbar from "$lib/components/Navbar.svelte";
  import Hero from "$lib/components/Hero.svelte";
  import Showcase from "$lib/components/Showcase.svelte";
  import CoreFeatures from "$lib/components/CoreFeatures.svelte";
  import Extensions from "$lib/components/Extensions.svelte";
  import AISection from "$lib/components/AISection.svelte";
  import Testimonials from "$lib/components/Testimonials.svelte";
  import Automate from "$lib/components/Automate.svelte";
  import MoreFeatures from "$lib/components/MoreFeatures.svelte";
  import Community from "$lib/components/Community.svelte";
  import Developer from "$lib/components/Developer.svelte";
  import KeyboardCTA from "$lib/components/KeyboardCTA.svelte";
  import Footer from "$lib/components/Footer.svelte";
</script>

<div class="bg-[#050505] min-h-screen text-white font-sans selection:bg-red-500/30 selection:text-red-200">
  <Navbar />
  <main>
    <Hero />
    <Showcase />
    <CoreFeatures />
    <Extensions />
    <AISection />
    <Testimonials />
    <Automate />
    <MoreFeatures />
    <Community />
    <Developer />
    <KeyboardCTA />
  </main>
  <Footer />
</div>

<style>
  :global(body) {
    background-color: #050505;
    color: white;
  }
</style>

