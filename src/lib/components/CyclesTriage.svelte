<section class="py-24 border-t border-white/5">
  <div class="max-w-[1200px] mx-auto px-6 grid grid-cols-1 md:grid-cols-2 gap-12">
    <!-- Performance Metrics Card -->
    <div>
      <h3 class="text-2xl font-medium mb-3">Real-time performance metrics</h3>
      <p class="text-gray-400 mb-8">Monitor system health with instant visibility into latency, throughput, and error rates.</p>
      
      <div class="bg-[#0e1012] border border-white/10 rounded-xl p-6 h-[350px] relative overflow-hidden flex flex-col">
        <div class="flex items-center justify-between mb-6">
            <div class="flex items-center gap-2">
                <span class="text-white font-medium">API Gateway</span>
            </div>
            <div class="flex items-center gap-4 text-xs">
                <div class="flex items-center gap-1.5 text-secondary-400"><span class="w-1.5 h-1.5 rounded-full bg-secondary-500"></span> Latency</div>
                <div class="flex items-center gap-1.5 text-primary-400"><span class="w-1.5 h-1.5 rounded-full bg-primary-500"></span> Errors</div>
                <div class="flex items-center gap-1.5 text-white"><span class="w-1.5 h-1.5 rounded-full bg-white"></span> Throughput</div>
            </div>
        </div>
        
        <!-- Graph Mockup -->
        <div class="flex-1 relative w-full">
            <!-- Grid Lines -->
            <div class="absolute inset-0 flex flex-col justify-between pointer-events-none">
                <div class="w-full h-[1px] bg-white/5"></div>
                <div class="w-full h-[1px] bg-white/5"></div>
                <div class="w-full h-[1px] bg-white/5"></div>
                <div class="w-full h-[1px] bg-white/5"></div>
            </div>
            
            <!-- Lines -->
            <svg class="w-full h-full overflow-visible" preserveAspectRatio="none">
                <!-- Throughput Line (White) -->
                <path d="M0,80 C50,78 100,75 150,73 C200,70 250,68 300,65 C350,63 400,60 450,58" fill="none" stroke="#ffffff" stroke-width="2" opacity="0.5" />
                
                <!-- Latency Line (Cyan) -->
                <path d="M0,90 C50,85 100,80 150,70 C200,60 250,55 300,50 C350,48 400,45 450,43" fill="none" stroke="#06b6d4" stroke-width="2" />
                
                <!-- Error Line (Pink) -->
                <path d="M0,95 C50,94 100,93 150,92 C200,90 250,88 300,85 C350,82 400,78 450,75" fill="none" stroke="#ec4899" stroke-width="2" />
            </svg>
            
            <!-- Hover Effect (Vertical Line) -->
            <div class="absolute top-0 bottom-0 left-2/3 w-[1px] bg-white/20"></div>
            <div class="absolute top-[25%] left-2/3 -translate-x-1/2 w-2 h-2 bg-primary-500 rounded-full ring-4 ring-black"></div>
            <div class="absolute top-[43%] left-2/3 -translate-x-1/2 w-2 h-2 bg-secondary-500 rounded-full ring-4 ring-black"></div>
        </div>
      </div>
    </div>

    <!-- Trace Analysis Card -->
    <div>
      <h3 class="text-2xl font-medium mb-3">Distributed trace analysis</h3>
      <p class="text-gray-400 mb-8">Follow requests across services with full context. Identify bottlenecks and optimize performance.</p>
      
      <div class="bg-[#0e1012] border border-white/10 rounded-xl p-6 h-[350px] relative overflow-hidden">
        <div class="text-sm font-medium text-white mb-4">Trace Details</div>
        
        <div class="bg-[#1a1c1e] border border-white/10 rounded-lg p-4 shadow-xl relative z-10">
            <div class="text-sm text-white mb-1 flex items-center gap-2">
                <span class="font-mono text-secondary-400">POST /api/checkout</span>
                <span class="px-1.5 py-0.5 bg-primary-500/10 text-primary-400 text-[10px] rounded border border-primary-500/20">2.4s</span>
            </div>
            <div class="flex items-center gap-2 text-xs text-gray-500 mb-4">
                <span>trace_id: 7f8a9b2c3d4e5f6g</span>
            </div>
            
            <div class="space-y-2">
                <div class="flex items-center gap-2 text-xs">
                    <div class="w-2 h-8 bg-secondary-500/30 rounded"></div>
                    <span class="text-gray-400 flex-1">api-gateway</span>
                    <span class="text-secondary-400">142ms</span>
                </div>
                <div class="flex items-center gap-2 text-xs ml-4">
                    <div class="w-2 h-16 bg-primary-500/30 rounded"></div>
                    <span class="text-gray-400 flex-1">payment-service</span>
                    <span class="text-primary-400">1.8s</span>
                </div>
                <div class="flex items-center gap-2 text-xs ml-8">
                    <div class="w-2 h-12 bg-white/30 rounded"></div>
                    <span class="text-gray-400 flex-1">database</span>
                    <span class="text-white">1.6s</span>
                </div>
            </div>
        </div>
        
        <!-- Action Menu Mockup -->
        <div class="absolute top-1/2 left-1/2 -translate-x-1/2 translate-y-10 bg-[#252729] border border-white/10 rounded-lg shadow-2xl p-1 w-48 z-20">
            <div class="flex items-center gap-2 px-2 py-1.5 hover:bg-white/10 rounded cursor-pointer text-xs text-white">
                <svg viewBox="0 0 16 16" class="w-3 h-3 fill-current"><path d="M8 1a7 7 0 1 0 0 14A7 7 0 0 0 8 1zM7 4.5a.5.5 0 0 1 1 0v3.793l1.854 1.853a.5.5 0 0 1-.708.708l-2-2A.5.5 0 0 1 7 8.5v-4z"/></svg>
                View full trace
            </div>
             <div class="flex items-center gap-2 px-2 py-1.5 hover:bg-white/10 rounded cursor-pointer text-xs text-white">
                <svg viewBox="0 0 16 16" class="w-3 h-3 fill-current"><path d="M8 1a7 7 0 1 0 0 14A7 7 0 0 0 8 1zM7 4.5a.5.5 0 0 1 1 0v3.793l1.854 1.853a.5.5 0 0 1-.708.708l-2-2A.5.5 0 0 1 7 8.5v-4z"/></svg>
                Related logs
            </div>
             <div class="flex items-center gap-2 px-2 py-1.5 hover:bg-white/10 rounded cursor-pointer text-xs text-white">
                <svg viewBox="0 0 16 16" class="w-3 h-3 fill-current"><path d="M8 1a7 7 0 1 0 0 14A7 7 0 0 0 8 1zM7 4.5a.5.5 0 0 1 1 0v3.793l1.854 1.853a.5.5 0 0 1-.708.708l-2-2A.5.5 0 0 1 7 8.5v-4z"/></svg>
                Create alert
            </div>
        </div>
      </div>
    </div>
  </div>
</section>
