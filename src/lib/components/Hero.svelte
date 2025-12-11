<script>
  // Hero component
</script>

<section class="pt-32 pb-16 md:pt-40 md:pb-24 overflow-hidden">
  <div class="container-custom flex flex-col items-center text-center">
    
    <!-- Badge -->
    <div class="inline-flex items-center gap-2 px-4 py-2 rounded-full bg-gray-50 border border-gray-200 text-gray-700 text-xs font-medium mb-8">
      <span class="flex items-center gap-1">
        <span class="w-2 h-2 rounded-full bg-green-500 animate-pulse"></span>
        Trusted by 140+ consumer brands
      </span>
    </div>

    <!-- Headline -->
    <h1 class="text-5xl md:text-7xl font-bold tracking-tight text-gray-900 mb-6 max-w-5xl mx-auto leading-[1.1]">
      Autonomous AI employees for <br class="hidden md:block" /> 
      <span class="relative inline-block">
        customer operations
        <svg class="absolute -bottom-2 left-0 w-full" height="12" viewBox="0 0 400 12" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path d="M2 10C50 5 150 2 200 5C250 8 350 4 398 8" stroke="oklch(0.696 0.17 162.48)" stroke-width="3" stroke-linecap="round"/>
        </svg>
      </span>
    </h1>

    <!-- Subheadline -->
    <p class="text-lg md:text-xl text-gray-500 mb-10 max-w-3xl mx-auto leading-relaxed">
      Self-assembling AI platform that manages omnichannel engagement and workflows. 
      <span class="font-semibold text-gray-700">72 hours to deploy. 90 days to 90% automation.</span> Zero engineering lift.
    </p>

    <!-- Buttons -->
    <div class="flex flex-col sm:flex-row items-center gap-4 mb-20">
      <a href="mailto:prashanth@sagepilot.ai" class="px-6 py-3 text-sm font-bold bg-black text-white rounded hover:bg-gray-800 transition-colors uppercase tracking-wide shadow-lg">
        Book a Demo
      </a>
      <a href="mailto:support@sagepilot.ai" class="px-6 py-3 text-sm font-bold border border-gray-300 text-gray-700 rounded hover:border-gray-400 transition-colors uppercase tracking-wide bg-white">
        Contact Sales
      </a>
    </div>

    <!-- Hero Image / UI Mockup -->
    <div class="relative w-full max-w-5xl mx-auto rounded-xl shadow-2xl border border-gray-200 bg-white overflow-hidden perspective-1000">
      <!-- Browser Chrome -->
      <div class="bg-gray-50 border-b border-gray-200 px-4 py-3 flex items-center gap-2">
        <div class="flex gap-1.5">
          <div class="w-3 h-3 rounded-full bg-red-400"></div>
          <div class="w-3 h-3 rounded-full bg-yellow-400"></div>
          <div class="w-3 h-3 rounded-full bg-green-400"></div>
        </div>
        <div class="flex-1 text-center">
          <div class="inline-flex items-center justify-center px-3 py-0.5 rounded bg-white border border-gray-200 text-[10px] text-gray-400 font-mono shadow-sm">
            sagepilot.ai/platform
          </div>
        </div>
      </div>

      <!-- App Interface Mockup -->
      <div class="flex h-[500px] md:h-[600px] text-left bg-white">
        <!-- Sidebar -->
        <div class="w-16 md:w-64 border-r border-gray-100 bg-gray-50/50 p-4 hidden md:flex flex-col gap-4">
            <div class="flex items-center gap-2 mb-4">
                <div class="w-6 h-6 rounded bg-gray-200"></div>
                <div class="h-3 w-20 bg-gray-200 rounded"></div>
            </div>
            {#each [1, 2, 3, 4, 5] as i}
            <div class="flex items-center gap-3 p-2 rounded hover:bg-gray-100">
                <div class="w-4 h-4 rounded bg-gray-200"></div>
                <div class="h-2 w-24 bg-gray-100 rounded"></div>
            </div>
            {/each}
        </div>

        <!-- Main Content -->
        <div class="flex-1 flex flex-col">
            <!-- Header -->
            <div class="h-14 border-b border-gray-100 flex items-center px-6 justify-between">
                <div class="flex items-center gap-3">
                    <div class="w-8 h-8 rounded-full bg-orange-100 flex items-center justify-center text-orange-600 font-bold text-xs">AA</div>
                    <div>
                        <div class="h-3 w-32 bg-gray-200 rounded mb-1"></div>
                        <div class="h-2 w-20 bg-gray-100 rounded"></div>
                    </div>
                </div>
            </div>
            <!-- Chat Area -->
            <div class="flex-1 p-6 bg-white relative">
                <!-- Message -->
                <div class="flex gap-4 mb-6">
                    <div class="w-8 h-8 rounded-full bg-gray-200 flex-shrink-0"></div>
                    <div class="flex-1">
                        <div class="flex items-center gap-2 mb-1">
                            <div class="h-3 w-24 bg-gray-200 rounded"></div>
                            <div class="h-2 w-12 bg-gray-100 rounded"></div>
                        </div>
                        <div class="h-2 w-full max-w-md bg-gray-100 rounded mb-2"></div>
                        <div class="h-2 w-full max-w-sm bg-gray-100 rounded"></div>
                    </div>
                </div>

                <!-- AI Response Box (Dark) -->
                <div class="bg-[#1C1C1C] rounded-lg p-4 text-gray-300 shadow-xl border border-gray-800 max-w-2xl mx-auto mt-8">
                    <div class="flex items-center justify-between mb-4 border-b border-gray-700 pb-3">
                        <div class="flex items-center gap-2 text-xs font-medium text-gray-400">
                            <div class="w-4 h-4 rounded-full bg-primary flex items-center justify-center text-white font-bold text-[10px]">AI</div>
                            AI Employee Assistant
                        </div>
                        <div class="text-[10px] text-gray-500">⌘K</div>
                    </div>
                    <div class="space-y-3 mb-6">
                        <div class="text-sm text-gray-300">Analyzing customer conversation patterns...</div>
                        <div class="text-xs text-gray-500">• 47 conversations processed today</div>
                        <div class="text-xs text-gray-500">• 3 escalations identified</div>
                    </div>
                    <div class="relative">
                        <input type="text" placeholder="Ask me anything about your customers..." class="w-full bg-transparent border-none text-sm text-white placeholder-gray-500 focus:ring-0 p-0" />
                        <div class="absolute right-0 top-0 flex gap-2">
                             <div class="w-4 h-4 border border-gray-600 rounded text-[10px] flex items-center justify-center text-gray-500">↵</div>
                        </div>
                    </div>
                </div>
            </div>
            
            <!-- Reply Box -->
            <div class="h-16 border-t border-gray-100 px-6 flex items-center gap-4">
                 <div class="flex-1 h-10 bg-gray-50 rounded border border-gray-200"></div>
                 <div class="w-20 h-10 bg-plain-green rounded opacity-20"></div>
            </div>
        </div>

        <!-- Right Sidebar -->
        <div class="w-72 border-l border-gray-100 bg-white p-4 hidden lg:block">
            <div class="space-y-6">
                <div>
                    <div class="h-3 w-20 bg-gray-200 rounded mb-3"></div>
                    <div class="space-y-2">
                        <div class="flex justify-between"><div class="h-2 w-16 bg-gray-100 rounded"></div><div class="h-2 w-12 bg-gray-100 rounded"></div></div>
                        <div class="flex justify-between"><div class="h-2 w-16 bg-gray-100 rounded"></div><div class="h-2 w-12 bg-gray-100 rounded"></div></div>
                        <div class="flex justify-between"><div class="h-2 w-16 bg-gray-100 rounded"></div><div class="h-2 w-12 bg-gray-100 rounded"></div></div>
                    </div>
                </div>
                <hr class="border-gray-100"/>
                <div>
                    <div class="h-3 w-20 bg-gray-200 rounded mb-3"></div>
                    <div class="flex gap-2 flex-wrap">
                        <div class="h-6 w-16 bg-gray-50 border border-gray-200 rounded-full"></div>
                        <div class="h-6 w-20 bg-gray-50 border border-gray-200 rounded-full"></div>
                        <div class="h-6 w-12 bg-gray-50 border border-gray-200 rounded-full"></div>
                    </div>
                </div>
            </div>
        </div>
      </div>
    </div>
  </div>
</section>
