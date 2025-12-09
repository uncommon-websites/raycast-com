<script lang="ts">
  import { onMount } from 'svelte';

  let isScrolled = false;

  onMount(() => {
    const handleScroll = () => {
      isScrolled = window.scrollY > 20;
    };
    window.addEventListener('scroll', handleScroll);
    return () => window.removeEventListener('scroll', handleScroll);
  });
</script>

<nav class="fixed top-0 left-0 right-0 z-50 transition-all duration-300 border-b border-transparent {isScrolled ? 'bg-[#050505]/80 backdrop-blur-md border-white/10' : 'bg-transparent'}">
  <div class="max-w-7xl mx-auto px-6 h-16 flex items-center justify-between">
    <!-- Logo -->
    <div class="flex items-center gap-8">
      <a href="/" class="text-white font-bold text-xl flex items-center gap-2">
        <svg viewBox="0 0 24 24" fill="none" class="w-6 h-6 text-white">
          <path d="M21 12C21 16.9706 16.9706 21 12 21C7.02944 21 3 16.9706 3 12C3 7.02944 7.02944 3 12 3C16.9706 3 21 7.02944 21 12Z" stroke="currentColor" stroke-width="2"/>
          <path d="M15 9L9 15" stroke="currentColor" stroke-width="2" stroke-linecap="round"/>
        </svg>
        <span class="sr-only">Raycast</span>
      </a>

      <!-- Desktop Nav -->
      <div class="hidden md:flex items-center gap-6 text-[13px] font-medium text-gray-400">
        <a href="#store" class="hover:text-white transition-colors">Store</a>
        <a href="#pro" class="hover:text-white transition-colors">Pro</a>
        <a href="#teams" class="hover:text-white transition-colors">Teams</a>
        <a href="#developers" class="hover:text-white transition-colors">Developers</a>
        <a href="#blog" class="hover:text-white transition-colors">Blog</a>
        <a href="#pricing" class="hover:text-white transition-colors">Pricing</a>
      </div>
    </div>

    <!-- Right Side -->
    <div class="flex items-center gap-4 text-[13px] font-medium">
      <a href="#login" class="hidden md:block text-gray-400 hover:text-white transition-colors">Log in</a>
      <a href="#download" class="bg-white text-black px-3 py-1.5 rounded-md hover:bg-gray-200 transition-colors font-semibold">Download</a>
    </div>
  </div>
</nav>
