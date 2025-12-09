<script lang="ts">
</script>

<section class="py-24 bg-[#050505] relative overflow-hidden">
  <!-- Background Glow -->
  <div class="absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 w-full h-full max-w-4xl max-h-[600px] bg-red-500/5 blur-[120px] rounded-full pointer-events-none"></div>

  <div class="max-w-6xl mx-auto px-6 relative z-10">
    <div class="text-center mb-16">
      <div class="inline-flex items-center gap-2 bg-red-500/10 text-red-500 px-3 py-1 rounded-full text-xs font-semibold mb-4 border border-red-500/20">
        <svg class="w-3 h-3" fill="currentColor" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-2 15l-5-5 1.41-1.41L10 14.17l7.59-7.59L19 8l-9 9z"></path></svg>
        New
      </div>
      <h2 class="text-4xl md:text-5xl font-bold text-white mb-4 tracking-tight">Your Mac just got smarter.</h2>
      <p class="text-xl text-gray-400">AI where it's most useful - on your Mac.</p>
    </div>

    <div class="bg-[#0A0A0A] border border-white/10 rounded-2xl overflow-hidden shadow-2xl mb-12">
        <div class="grid grid-cols-1 md:grid-cols-2">
            <div class="p-8 md:p-12 flex flex-col justify-center">
                <h3 class="text-2xl font-bold text-white mb-4">Ask anything, anytime, anywhere.</h3>
                <p class="text-gray-400 mb-8 leading-relaxed">
                    Invoke AI anywhere on your Mac. Ask questions, generate code, translate languages, and more.
                </p>
                
                <div class="space-y-6">
                    <div class="flex gap-4">
                        <div class="w-6 h-6 rounded-full bg-white/10 flex items-center justify-center text-white text-xs mt-1">1</div>
                        <div>
                            <h4 class="text-white font-medium mb-1">Always context-aware</h4>
                            <p class="text-sm text-gray-500">Raycast AI knows what you're looking at and can help you with it.</p>
                        </div>
                    </div>
                    <div class="flex gap-4">
                        <div class="w-6 h-6 rounded-full bg-white/10 flex items-center justify-center text-white text-xs mt-1">2</div>
                        <div>
                            <h4 class="text-white font-medium mb-1">Your information is private</h4>
                            <p class="text-sm text-gray-500">Your data is encrypted and secure. We don't train models on your data.</p>
                        </div>
                    </div>
                </div>

                <div class="mt-8">
                    <a href="#" class="text-white border-b border-white/30 hover:border-white pb-0.5 transition-colors">More about AI -></a>
                </div>
            </div>
            
            <div class="bg-[#111] relative min-h-[400px] border-l border-white/5">
                <!-- Chat Interface Mockup -->
                <div class="absolute inset-0 bg-gradient-to-br from-[#FF6363]/5 to-transparent"></div>
                <div class="absolute inset-4 bg-[#1A1A1A] rounded-xl border border-white/10 shadow-2xl p-4 flex flex-col">
                    <div class="flex items-center gap-3 border-b border-white/5 pb-4 mb-4">
                        <div class="w-8 h-8 rounded bg-red-500 flex items-center justify-center text-white font-bold">AI</div>
                        <div class="text-white font-medium">Raycast AI</div>
                    </div>
                    <div class="flex-1 space-y-4 overflow-hidden">
                        <div class="bg-white/5 rounded-lg p-3 text-sm text-gray-300 self-end ml-8">
                            How do I center a div in CSS?
                        </div>
                        <div class="bg-transparent rounded-lg p-3 text-sm text-gray-300 mr-8 border border-white/5">
                            <p class="mb-2">You can center a div using Flexbox:</p>
                            <pre class="bg-black/50 p-2 rounded text-xs font-mono text-gray-400">
.container &#123;
  display: flex;
  justify-content: center;
  align-items: center;
&#125;</pre>
                        </div>
                    </div>
                    <div class="mt-4 pt-4 border-t border-white/5">
                        <div class="bg-[#0A0A0A] border border-white/10 rounded px-3 py-2 text-sm text-gray-500 flex justify-between items-center">
                            <span>Ask AI...</span>
                            <span class="text-xs border border-white/10 rounded px-1">↵</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
  </div>
</section>
