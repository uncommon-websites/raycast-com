<script lang="ts">
</script>

<section class="py-24 bg-[#050505] relative overflow-hidden">
  <div class="max-w-6xl mx-auto px-6">
    <div class="flex flex-col md:flex-row justify-between items-end mb-12">
      <div>
        <h2 class="text-3xl md:text-4xl font-bold text-white mb-4 tracking-tight">There's an extension for that.</h2>
        <p class="text-gray-400 max-w-xl">Use your favorite tools without even opening them.</p>
      </div>
      
      <div class="flex gap-2 mt-6 md:mt-0">
        <button class="px-4 py-1.5 rounded-full bg-white/10 text-white text-sm font-medium hover:bg-white/20 transition-colors">Productivity</button>
        <button class="px-4 py-1.5 rounded-full bg-transparent border border-white/10 text-gray-400 text-sm font-medium hover:text-white hover:border-white/20 transition-colors">Engineering</button>
        <button class="px-4 py-1.5 rounded-full bg-transparent border border-white/10 text-gray-400 text-sm font-medium hover:text-white hover:border-white/20 transition-colors">Design</button>
        <button class="px-4 py-1.5 rounded-full bg-transparent border border-white/10 text-gray-400 text-sm font-medium hover:text-white hover:border-white/20 transition-colors">Writing</button>
      </div>
    </div>

    <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
      <!-- Card 1: Linear -->
      <div class="bg-[#0A0A0A] border border-white/5 rounded-2xl p-6 hover:border-white/20 transition-all group relative overflow-hidden">
        <div class="absolute top-0 right-0 p-4 opacity-50 group-hover:opacity-100 transition-opacity">
            <svg class="w-5 h-5 text-gray-500" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14"></path></svg>
        </div>
        <div class="mb-6">
            <div class="w-10 h-10 bg-[#5E6AD2] rounded-lg flex items-center justify-center mb-3">
                <svg class="w-6 h-6 text-white" fill="currentColor" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-1 15h-2v-6h2v6zm0-8h-2V7h2v2z"></path></svg>
            </div>
            <h3 class="text-xl font-bold text-white mb-2">Linear</h3>
            <p class="text-sm text-gray-400 leading-relaxed">Create, search and modify your issues without leaving your keyboard.</p>
        </div>
        <div class="h-32 bg-[#151515] rounded-lg border border-white/5 relative overflow-hidden">
            <!-- Abstract Linear UI -->
            <div class="absolute inset-0 bg-gradient-to-br from-[#5E6AD2]/10 to-transparent"></div>
            <div class="p-3">
                <div class="w-3/4 h-2 bg-white/10 rounded mb-2"></div>
                <div class="w-1/2 h-2 bg-white/10 rounded"></div>
            </div>
        </div>
      </div>

      <!-- Card 2: Google Translate -->
      <div class="bg-[#0A0A0A] border border-white/5 rounded-2xl p-6 hover:border-white/20 transition-all group relative overflow-hidden">
        <div class="absolute top-0 right-0 p-4 opacity-50 group-hover:opacity-100 transition-opacity">
            <svg class="w-5 h-5 text-gray-500" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14"></path></svg>
        </div>
        <div class="mb-6">
            <div class="w-10 h-10 bg-[#4285F4] rounded-lg flex items-center justify-center mb-3">
                <span class="text-white font-bold text-lg">G</span>
            </div>
            <h3 class="text-xl font-bold text-white mb-2">Google Translate</h3>
            <p class="text-sm text-gray-400 leading-relaxed">Use Google Translate to effortlessly translate into multiple languages.</p>
        </div>
        <div class="h-32 bg-[#151515] rounded-lg border border-white/5 relative overflow-hidden flex flex-col justify-center px-4">
             <div class="text-xs text-gray-500 mb-1">English</div>
             <div class="text-sm text-white mb-2">Hello World</div>
             <div class="h-px bg-white/10 w-full mb-2"></div>
             <div class="text-xs text-gray-500 mb-1">French</div>
             <div class="text-sm text-white">Bonjour le monde</div>
        </div>
      </div>

      <!-- Card 3: Spotify -->
      <div class="bg-[#0A0A0A] border border-white/5 rounded-2xl p-6 hover:border-white/20 transition-all group relative overflow-hidden">
        <div class="absolute top-0 right-0 p-4 opacity-50 group-hover:opacity-100 transition-opacity">
            <svg class="w-5 h-5 text-gray-500" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14"></path></svg>
        </div>
        <div class="mb-6">
            <div class="w-10 h-10 bg-[#1DB954] rounded-lg flex items-center justify-center mb-3">
                <svg class="w-6 h-6 text-white" fill="currentColor" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm4.59 14.42c-.2.3-.59.4-.89.2-2.43-1.48-5.49-1.82-9.09-1-3-.07-.53-.44-.24-.73.28-.29.67-.21.96.06 3.96.9 7.36 1.27 10.23.41.3-.19.69-.1.89.2zm1.27-2.83c-.25.41-.78.54-1.19.29-2.8-1.72-7.06-2.22-10.37-1.21-.46.14-.95-.12-1.09-.58-.14-.46.12-.95.58-1.09 3.82-1.16 8.56-.61 11.78 1.36.41.25.54.78.29 1.19zm.13-2.97c-3.35-1.99-8.88-2.17-12.08-1.2-.52.16-1.07-.13-1.23-.65-.16-.52.13-1.07.65-1.23 3.73-1.12 9.85-.92 13.75 1.4.46.27.61.87.34 1.34-.27.46-.87.61-1.34.34z"></path></svg>
            </div>
            <h3 class="text-xl font-bold text-white mb-2">Spotify</h3>
            <p class="text-sm text-gray-400 leading-relaxed">Search for music and podcasts, browse your library, and control playback.</p>
        </div>
        <div class="h-32 bg-[#151515] rounded-lg border border-white/5 relative overflow-hidden flex items-center justify-center">
            <div class="flex items-center gap-4">
                <div class="w-12 h-12 bg-gray-700 rounded shadow-lg"></div>
                <div class="flex gap-2">
                    <svg class="w-6 h-6 text-gray-400" fill="currentColor" viewBox="0 0 24 24"><path d="M6 6h2v12H6zm3.5 6l8.5 6V6z"></path></svg>
                    <svg class="w-6 h-6 text-white" fill="currentColor" viewBox="0 0 24 24"><path d="M8 5v14l11-7z"></path></svg>
                    <svg class="w-6 h-6 text-gray-400" fill="currentColor" viewBox="0 0 24 24"><path d="M6 18l8.5-6L6 6v12zM16 6v12h2V6h-2z"></path></svg>
                </div>
            </div>
        </div>
      </div>
    </div>

    <div class="mt-12 text-center">
        <a href="#" class="text-gray-500 hover:text-white transition-colors text-sm font-medium">Browse the store -></a>
    </div>
  </div>
</section>
