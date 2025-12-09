<script lang="ts">
</script>

<section class="py-20 relative">
  <div class="max-w-6xl mx-auto px-6 text-center">
    <h2 class="text-3xl md:text-4xl font-bold text-white mb-4 tracking-tight">Take shortcuts, not detours.</h2>
    <p class="text-gray-400 mb-12">One interface, everything you need.</p>

    <div class="relative rounded-xl overflow-hidden shadow-2xl border border-white/10 bg-[#0A0A0A]">
      <!-- Mockup of the interface -->
      <div class="aspect-[16/10] w-full bg-[#111] relative flex flex-col">
        <!-- Window Bar -->
        <div class="h-8 bg-[#1A1A1A] flex items-center px-4 gap-2 border-b border-white/5">
            <div class="flex gap-1.5">
                <div class="w-3 h-3 rounded-full bg-[#FF5F57]"></div>
                <div class="w-3 h-3 rounded-full bg-[#FEBC2E]"></div>
                <div class="w-3 h-3 rounded-full bg-[#28C840]"></div>
            </div>
        </div>
        
        <!-- Content -->
        <div class="flex-1 p-8 flex items-center justify-center relative overflow-hidden">
            <!-- Background Elements inside the mockup -->
            <div class="absolute inset-0 bg-gradient-to-br from-[#1A1A1A] to-[#050505]"></div>
            
            <!-- The Raycast Bar -->
            <div class="w-[600px] bg-[#151515]/90 backdrop-blur-xl rounded-xl border border-white/10 shadow-2xl overflow-hidden relative z-10">
                <div class="h-14 border-b border-white/5 flex items-center px-4 gap-3">
                    <svg class="w-5 h-5 text-gray-400" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"></path></svg>
                    <input type="text" placeholder="Type to filter..." class="bg-transparent border-none outline-none text-white w-full placeholder-gray-500 text-lg" value="Linear" />
                </div>
                <div class="p-2">
                    <div class="text-xs font-semibold text-gray-500 px-2 py-1 uppercase tracking-wider">Today</div>
                    <!-- List Items -->
                    <div class="flex items-center gap-3 px-2 py-2 rounded-lg bg-white/5 text-white">
                        <div class="w-5 h-5 bg-purple-500 rounded flex items-center justify-center text-[10px]">L</div>
                        <span class="flex-1">Create Issue</span>
                        <span class="text-gray-500 text-sm">Linear</span>
                    </div>
                    <div class="flex items-center gap-3 px-2 py-2 rounded-lg hover:bg-white/5 text-gray-300 transition-colors">
                        <div class="w-5 h-5 bg-blue-500 rounded flex items-center justify-center text-[10px]">J</div>
                        <span class="flex-1">Search Issues</span>
                        <span class="text-gray-500 text-sm">Jira</span>
                    </div>
                     <div class="flex items-center gap-3 px-2 py-2 rounded-lg hover:bg-white/5 text-gray-300 transition-colors">
                        <div class="w-5 h-5 bg-green-500 rounded flex items-center justify-center text-[10px]">S</div>
                        <span class="flex-1">Search Tracks</span>
                        <span class="text-gray-500 text-sm">Spotify</span>
                    </div>
                </div>
                
                <!-- Footer of bar -->
                <div class="h-10 border-t border-white/5 bg-[#1A1A1A]/50 flex items-center justify-between px-4 text-xs text-gray-500">
                    <div class="flex gap-2">
                         <span class="bg-white/10 px-1.5 py-0.5 rounded text-gray-300">↵</span>
                         <span>Open</span>
                    </div>
                    <div class="flex gap-2">
                         <span class="bg-white/10 px-1.5 py-0.5 rounded text-gray-300">⌘ K</span>
                         <span>Actions</span>
                    </div>
                </div>
            </div>

            <!-- Floating Elements (Abstract representation of other windows/tools) -->
            <div class="absolute top-10 right-10 w-40 h-20 bg-red-500/10 rounded-lg blur-xl"></div>
             <div class="absolute bottom-10 left-10 w-40 h-20 bg-blue-500/10 rounded-lg blur-xl"></div>
        </div>
      </div>
    </div>
    
    <div class="mt-8 text-sm text-gray-500 font-mono">
        remember everything &nbsp;|&nbsp; keep playing &nbsp;|&nbsp; window management &nbsp;|&nbsp; clipboard history
    </div>
  </div>
</section>
