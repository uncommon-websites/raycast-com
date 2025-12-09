<script lang="ts">
</script>

<section class="py-24 bg-[#050505]">
  <div class="max-w-6xl mx-auto px-6">
    <div class="mb-16">
      <h2 class="text-3xl md:text-4xl font-bold text-white mb-4 tracking-tight">Don't repeat yourself.</h2>
      <p class="text-gray-400">Automate the things you do all the time.</p>
    </div>

    <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
      <!-- Snippets -->
      <div class="bg-[#0A0A0A] border border-white/10 rounded-2xl p-8 relative overflow-hidden h-[400px] group">
         <div class="absolute top-0 right-0 p-6 z-10">
            <svg class="w-6 h-6 text-gray-600" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path></svg>
         </div>
         <h3 class="text-xl font-bold text-white mb-2">Snippets</h3>
         <p class="text-gray-400 text-sm mb-8 max-w-xs">Stop typing the same thing? Create a snippet and insert it by simply typing a keyword.</p>
         
         <!-- Visual -->
         <div class="absolute bottom-0 left-0 right-0 h-48 bg-[#111] border-t border-white/5 p-4 flex flex-col gap-2">
            <div class="bg-[#1A1A1A] rounded p-3 border border-white/5 flex justify-between items-center">
                <span class="text-gray-400 text-sm">!em</span>
                <span class="text-white text-sm">example@raycast.com</span>
            </div>
             <div class="bg-[#1A1A1A] rounded p-3 border border-white/5 flex justify-between items-center">
                <span class="text-gray-400 text-sm">!addr</span>
                <span class="text-white text-sm">123 Main St, San Francisco...</span>
            </div>
         </div>
      </div>

      <!-- Clipboard History -->
      <div class="bg-[#0A0A0A] border border-white/10 rounded-2xl p-8 relative overflow-hidden h-[400px] group">
         <div class="absolute top-0 right-0 p-6 z-10">
            <svg class="w-6 h-6 text-gray-600" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5H7a2 2 0 00-2 2v12a2 2 0 002 2h10a2 2 0 002-2V7a2 2 0 00-2-2h-2M9 5a2 2 0 002 2h2a2 2 0 002-2M9 5a2 2 0 012-2h2a2 2 0 012 2"></path></svg>
         </div>
         <h3 class="text-xl font-bold text-white mb-2">Clipboard History</h3>
         <p class="text-gray-400 text-sm mb-8 max-w-xs">Never lose what you copied. Search and paste from your clipboard history.</p>
         
         <!-- Visual -->
         <div class="absolute bottom-0 left-0 right-0 h-48 bg-[#111] border-t border-white/5 p-4">
             <div class="space-y-2">
                 <div class="flex items-center gap-3 p-2 bg-white/5 rounded border border-white/5">
                     <div class="w-8 h-8 bg-blue-500/20 rounded flex items-center justify-center text-blue-500 text-xs">IMG</div>
                     <div class="flex-1 min-w-0">
                         <div class="text-white text-sm truncate">Screenshot 2023-10-25...</div>
                         <div class="text-gray-500 text-xs">Image</div>
                     </div>
                 </div>
                 <div class="flex items-center gap-3 p-2 rounded hover:bg-white/5 transition-colors">
                     <div class="w-8 h-8 bg-gray-700/50 rounded flex items-center justify-center text-gray-400 text-xs">TXT</div>
                     <div class="flex-1 min-w-0">
                         <div class="text-gray-300 text-sm truncate">https://raycast.com</div>
                         <div class="text-gray-500 text-xs">Link</div>
                     </div>
                 </div>
             </div>
         </div>
      </div>
    </div>
  </div>
</section>
