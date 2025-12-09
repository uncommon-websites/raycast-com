<script lang="ts">
</script>

<section class="py-24 bg-[#050505]">
  <div class="max-w-6xl mx-auto px-6">
    <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
      <!-- Text Block -->
      <div class="md:col-span-1 flex flex-col justify-center">
        <h2 class="text-3xl font-bold text-white mb-6 leading-tight tracking-tight">
          It's not about saving time. <br/>
          <span class="text-gray-500">It's about feeling like you're never wasting it.</span>
        </h2>
        <div>
            <button class="bg-[#1A1A1A] text-white px-4 py-2 rounded-md text-sm font-medium border border-white/10 hover:bg-[#252525] transition-colors flex items-center gap-2">
                <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 16v1a3 3 0 003 3h10a3 3 0 003-3v-1m-4-4l-4 4m0 0l-4-4m4 4V4"></path></svg>
                Download
            </button>
        </div>
      </div>

      <!-- Grid Block -->
      <div class="md:col-span-2 grid grid-cols-2 md:grid-cols-3 gap-4">
        <!-- Card 1: Calculator -->
        <div class="bg-[#0A0A0A] border border-white/5 rounded-xl p-6 hover:border-white/10 transition-colors group">
            <div class="w-8 h-8 bg-orange-500/20 text-orange-500 rounded-lg flex items-center justify-center mb-4 group-hover:scale-110 transition-transform">
                <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 7h6m0 10v-3m-3 3h.01M9 17h.01M9 14h.01M12 14h.01M15 11h.01M12 11h.01M9 11h.01M7 21h10a2 2 0 002-2V5a2 2 0 00-2-2H7a2 2 0 00-2 2v14a2 2 0 002 2z"></path></svg>
            </div>
            <h3 class="text-white font-medium mb-1">Calculator</h3>
            <p class="text-xs text-gray-500">Solve math, convert units.</p>
        </div>

        <!-- Card 2: Window Management -->
        <div class="bg-[#0A0A0A] border border-white/5 rounded-xl p-6 hover:border-white/10 transition-colors group">
            <div class="w-8 h-8 bg-blue-500/20 text-blue-500 rounded-lg flex items-center justify-center mb-4 group-hover:scale-110 transition-transform">
                <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2H6a2 2 0 01-2-2V6zM14 6a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2h-2a2 2 0 01-2-2V6zM4 16a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2H6a2 2 0 01-2-2v-2zM14 16a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2h-2a2 2 0 01-2-2v-2z"></path></svg>
            </div>
            <h3 class="text-white font-medium mb-1">Window Mgmt</h3>
            <p class="text-xs text-gray-500">Resize and organize.</p>
        </div>

        <!-- Card 3: File Search -->
        <div class="bg-[#0A0A0A] border border-white/5 rounded-xl p-6 hover:border-white/10 transition-colors group">
            <div class="w-8 h-8 bg-purple-500/20 text-purple-500 rounded-lg flex items-center justify-center mb-4 group-hover:scale-110 transition-transform">
                <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"></path></svg>
            </div>
            <h3 class="text-white font-medium mb-1">File Search</h3>
            <p class="text-xs text-gray-500">Find files instantly.</p>
        </div>

        <!-- Card 4: System -->
        <div class="bg-[#0A0A0A] border border-white/5 rounded-xl p-6 hover:border-white/10 transition-colors group">
            <div class="w-8 h-8 bg-gray-500/20 text-gray-400 rounded-lg flex items-center justify-center mb-4 group-hover:scale-110 transition-transform">
                <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6V4m0 2a2 2 0 100 4m0-4a2 2 0 110 4m-6 8a2 2 0 100-4m0 4a2 2 0 110-4m0 4v2m0-6V4m6 6v10m6-2a2 2 0 100-4m0 4a2 2 0 110-4m0 4v2m0-6V4"></path></svg>
            </div>
            <h3 class="text-white font-medium mb-1">System</h3>
            <p class="text-xs text-gray-500">Control your Mac.</p>
        </div>

        <!-- Card 5: Snippets -->
        <div class="bg-[#0A0A0A] border border-white/5 rounded-xl p-6 hover:border-white/10 transition-colors group">
            <div class="w-8 h-8 bg-yellow-500/20 text-yellow-500 rounded-lg flex items-center justify-center mb-4 group-hover:scale-110 transition-transform">
                <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5H7a2 2 0 00-2 2v12a2 2 0 002 2h10a2 2 0 002-2V7a2 2 0 00-2-2h-2M9 5a2 2 0 002 2h2a2 2 0 002-2M9 5a2 2 0 012-2h2a2 2 0 012 2"></path></svg>
            </div>
            <h3 class="text-white font-medium mb-1">Snippets</h3>
            <p class="text-xs text-gray-500">Expand text fast.</p>
        </div>

        <!-- Card 6: Floating Notes -->
        <div class="bg-[#0A0A0A] border border-white/5 rounded-xl p-6 hover:border-white/10 transition-colors group">
            <div class="w-8 h-8 bg-red-500/20 text-red-500 rounded-lg flex items-center justify-center mb-4 group-hover:scale-110 transition-transform">
                <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M11 5H6a2 2 0 00-2 2v11a2 2 0 002 2h11a2 2 0 002-2v-5m-1.414-9.414a2 2 0 112.828 2.828L11.828 15H9v-2.828l8.586-8.586z"></path></svg>
            </div>
            <h3 class="text-white font-medium mb-1">Floating Notes</h3>
            <p class="text-xs text-gray-500">Jot down ideas.</p>
        </div>
      </div>
    </div>
  </div>
</section>
