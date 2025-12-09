<script lang="ts">
</script>

<section class="py-32 bg-[#050505] relative overflow-hidden flex flex-col items-center text-center">
  <!-- Keyboard Visual (simplified with CSS) -->
  <div class="w-full max-w-5xl mb-12 relative opacity-50 hover:opacity-100 transition-opacity duration-700">
      <div class="grid grid-cols-10 gap-2 px-12">
          <!-- Row 1 -->
          {#each Array(10) as _, i}
            <div class="h-12 border border-white/10 rounded bg-[#111]"></div>
          {/each}
          <!-- Row 2 -->
          <div class="col-span-10 grid grid-cols-[1.5fr_repeat(10,1fr)_1.5fr] gap-2 mt-2">
             <div class="h-12 border border-white/10 rounded bg-[#111]"></div>
             {#each Array(10) as _, i}
                <div class="h-12 border border-white/10 rounded bg-[#111] flex items-center justify-center text-gray-700 font-mono text-xs">
                    {['Q','W','E','R','T','Y','U','I','O','P'][i]}
                </div>
             {/each}
             <div class="h-12 border border-white/10 rounded bg-[#111]"></div>
          </div>
           <!-- Row 3 -->
          <div class="col-span-10 grid grid-cols-[1.8fr_repeat(9,1fr)_2.2fr] gap-2 mt-2">
             <div class="h-12 border border-white/10 rounded bg-[#111]"></div>
             {#each Array(9) as _, i}
                <div class="h-12 border border-white/10 rounded bg-[#111] flex items-center justify-center text-gray-700 font-mono text-xs">
                    {['A','S','D','F','G','H','J','K','L'][i]}
                </div>
             {/each}
             <div class="h-12 border border-white/10 rounded bg-[#111]"></div>
          </div>
           <!-- Row 4 -->
          <div class="col-span-10 grid grid-cols-[2.2fr_repeat(7,1fr)_2.8fr] gap-2 mt-2">
             <div class="h-12 border border-white/10 rounded bg-[#111]"></div>
             {#each Array(7) as _, i}
                <div class="h-12 border border-white/10 rounded bg-[#111] flex items-center justify-center text-gray-700 font-mono text-xs">
                    {['Z','X','C','V','B','N','M'][i]}
                </div>
             {/each}
             <div class="h-12 border border-white/10 rounded bg-[#111]"></div>
          </div>
          <!-- Row 5 (Spacebar row) -->
           <div class="col-span-10 grid grid-cols-[1.5fr_1.5fr_1.5fr_6fr_1.5fr_1.5fr_1.5fr] gap-2 mt-2">
             <div class="h-12 border border-white/10 rounded bg-[#111]"></div>
             <div class="h-12 border border-white/10 rounded bg-[#111]"></div>
             <!-- Command Key Highlighted -->
             <div class="h-12 border border-red-500/50 rounded bg-gradient-to-t from-red-900/20 to-[#111] flex items-center justify-center text-white font-mono text-xs shadow-[0_0_15px_rgba(255,0,0,0.3)]">
                 command
             </div>
             <div class="h-12 border border-white/10 rounded bg-[#111]"></div>
             <div class="h-12 border border-white/10 rounded bg-[#111] flex items-center justify-center text-gray-700 font-mono text-xs">command</div>
             <div class="h-12 border border-white/10 rounded bg-[#111]"></div>
             <div class="h-12 border border-white/10 rounded bg-[#111]"></div>
          </div>
      </div>
  </div>

  <h2 class="text-4xl md:text-5xl font-bold text-white mb-6 tracking-tight">Take the short way.</h2>
  <p class="text-gray-400 mb-10">Download and use Raycast for free.</p>

  <div class="flex flex-col sm:flex-row items-center gap-4">
      <a href="#download-mac" class="bg-white text-black px-6 py-3 rounded-lg font-semibold hover:bg-gray-200 transition-colors flex items-center gap-2">
        Download for Mac
      </a>
      <a href="#download-windows" class="bg-[#1A1A1A] text-white border border-white/10 px-6 py-3 rounded-lg font-semibold hover:bg-[#252525] transition-colors flex items-center gap-2">
        Download for Windows (Beta)
      </a>
  </div>
  <div class="text-xs text-gray-500 font-mono mt-6">
      v1.88.0 &nbsp;|&nbsp; macOS 12+ &nbsp;|&nbsp; Install via Homebrew
  </div>
</section>
