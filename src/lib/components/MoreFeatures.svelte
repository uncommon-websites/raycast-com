<script lang="ts">
</script>

<section class="py-24 bg-[#050505]">
  <div class="max-w-6xl mx-auto px-6">
    <div class="grid grid-cols-1 md:grid-cols-2 gap-12 items-center">
      <div>
        <h2 class="text-3xl md:text-4xl font-bold text-white mb-6 tracking-tight">What else can Raycast do?</h2>
        <div class="space-y-2 text-xl md:text-2xl font-medium">
            <p class="text-white">It can take notes.</p>
            <p class="text-gray-600">Track your flights.</p>
            <p class="text-gray-600">Convert anything.</p>
            <p class="text-gray-600">Search files.</p>
            <p class="text-gray-600">Run scripts.</p>
            <p class="text-gray-600">Manage your windows.</p>
            <p class="text-gray-600">Plan your day.</p>
            <p class="text-gray-600">Remind you of stuff.</p>
        </div>
        <div class="mt-8">
            <a href="#" class="text-red-500 hover:text-red-400 transition-colors flex items-center gap-2 font-medium">
                <span class="bg-red-500/10 p-1 rounded">
                    <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path></svg>
                </span>
                Raycast Notes
            </a>
            <p class="text-gray-500 text-sm mt-2">The quickest way to capture a thought while working on something else. <a href="#" class="underline">Read more</a></p>
        </div>
      </div>

      <div class="relative">
          <div class="bg-[#0A0A0A] border border-white/10 rounded-2xl p-8 relative overflow-hidden h-[500px]">
              <!-- Visual representation of notes -->
              <div class="absolute inset-0 bg-gradient-to-b from-red-500/5 to-transparent"></div>
              <div class="relative z-10">
                  <h3 class="text-2xl font-bold text-white mb-6">Meeting notes</h3>
                  <p class="text-gray-400 mb-8">Make sure to go through <span class="text-red-400 bg-red-500/10 px-1 rounded">code review</span> after the meeting ends and <span class="bg-white/10 px-1 rounded text-gray-300">create tickets</span> for the next sprint.</p>
                  
                  <h4 class="text-white font-bold mb-4">Task list</h4>
                  <div class="space-y-3">
                      <div class="flex items-center gap-3">
                          <div class="w-5 h-5 rounded border border-red-500 bg-red-500/20 flex items-center justify-center text-red-500">
                              <svg class="w-3 h-3" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>
                          </div>
                          <span class="text-gray-400 line-through">Publish widget to the store</span>
                      </div>
                      <div class="flex items-center gap-3">
                          <div class="w-5 h-5 rounded border border-gray-600"></div>
                          <span class="text-white">Add analytics to the new feature</span>
                      </div>
                      <div class="flex items-center gap-3">
                          <div class="w-5 h-5 rounded border border-gray-600"></div>
                          <span class="text-white">Review the design for the new landing page</span>
                      </div>
                  </div>
              </div>
          </div>
      </div>
    </div>
  </div>
</section>
