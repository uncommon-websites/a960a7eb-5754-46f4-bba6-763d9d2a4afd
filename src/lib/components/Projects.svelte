<section class="py-24 border-t border-white/5">
  <div class="max-w-[1200px] mx-auto px-6 grid grid-cols-1 md:grid-cols-2 gap-16">
    <!-- Column 1 -->
    <div>
      <h3 class="text-2xl font-medium mb-3">Perses-compatible dashboards</h3>
      <p class="text-gray-400 mb-8">Build custom dashboards with full PromQL support and portable configurations. No vendor lock-in.</p>
      
      <div class="bg-[#0e1012] border border-white/10 rounded-xl p-6 h-[350px] relative overflow-hidden">
        <div class="space-y-4">
            <div class="flex items-center justify-between mb-6">
                <span class="text-lg font-medium">Service Dashboard</span>
                <span class="text-xs text-gray-500">Last 1h</span>
            </div>
            
            <div class="space-y-3 text-sm">
                <div class="flex items-center py-2 border-b border-white/5">
                    <div class="w-32 text-gray-500">Query</div>
                    <div class="flex items-center gap-2 flex-1">
                        <span class="text-xs font-mono text-secondary-400 bg-secondary-500/10 px-2 py-0.5 rounded border border-secondary-500/20">rate(http_requests[5m])</span>
                    </div>
                </div>
                
                <div class="flex items-center py-2 border-b border-white/5">
                    <div class="w-32 text-gray-500">Variables</div>
                    <div class="flex items-center gap-2">
                        <span class="px-2 py-0.5 bg-white/5 rounded text-xs text-gray-300 border border-white/5">service: api</span>
                        <span class="px-2 py-0.5 bg-white/5 rounded text-xs text-gray-300 border border-white/5">env: prod</span>
                    </div>
                </div>
                 
                <div class="flex py-2">
                    <div class="w-32 text-gray-500 shrink-0">Panels</div>
                    <div class="w-full space-y-2">
                        <div class="flex items-center justify-between text-xs">
                            <span class="text-gray-300 flex items-center gap-1.5"><span class="w-1.5 h-1.5 rounded-full bg-secondary-500"></span> Request Rate</span>
                            <span class="text-secondary-400">1.2k/s</span>
                        </div>
                        <div class="w-full h-8 bg-white/5 rounded overflow-hidden flex items-end gap-0.5 px-1 pb-1">
                            {#each [40, 55, 45, 60, 50, 65, 55, 70, 60, 75] as height}
                            <div class="flex-1 bg-secondary-500/50 rounded-t" style="height: {height}%"></div>
                            {/each}
                        </div>
                        
                        <div class="flex items-center justify-between text-xs mt-3">
                            <span class="text-gray-300 flex items-center gap-1.5"><span class="w-1.5 h-1.5 rounded-full bg-primary-500"></span> Error Rate</span>
                            <span class="text-primary-400">0.03%</span>
                        </div>
                         <div class="w-full h-8 bg-white/5 rounded overflow-hidden flex items-end gap-0.5 px-1 pb-1">
                            {#each [10, 8, 12, 5, 15, 8, 10, 6, 12, 8] as height}
                            <div class="flex-1 bg-primary-500/50 rounded-t" style="height: {height}%"></div>
                            {/each}
                        </div>
                        
                        <div class="flex items-center justify-between text-xs mt-3">
                            <span class="text-gray-300 flex items-center gap-1.5"><span class="w-1.5 h-1.5 rounded-full bg-white"></span> Latency (p95)</span>
                            <span class="text-white">124ms</span>
                        </div>
                         <div class="w-full h-1 bg-white/5 rounded-full overflow-hidden">
                            <div class="h-full bg-white/50 w-2/3"></div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
      </div>
    </div>

    <!-- Column 2 -->
    <div>
      <h3 class="text-2xl font-medium mb-3">Pre-built templates</h3>
      <p class="text-gray-400 mb-8">Start with ready-made dashboards for Kubernetes, databases, and cloud services. Customize as needed.</p>
      
      <div class="bg-[#0e1012] border border-white/10 rounded-xl p-6 h-[350px] relative overflow-hidden flex items-center justify-center">
        <!-- Dashboard Template Card Mockup -->
        <div class="bg-[#1a1c1e] border border-white/10 rounded-lg p-5 w-full max-w-sm shadow-2xl transform rotate-3 hover:rotate-0 transition-transform duration-500">
            <div class="flex items-center gap-3 mb-4">
                <div class="w-8 h-8 rounded-full bg-secondary-500/20 flex items-center justify-center text-secondary-500">
                    <svg viewBox="0 0 24 24" class="w-4 h-4 fill-current"><path d="M3 13h8V3H3v10zm0 8h8v-6H3v6zm10 0h8V11h-8v10zm0-18v6h8V3h-8z"/></svg>
                </div>
                <div>
                    <div class="text-sm font-medium text-white">Kubernetes Cluster</div>
                    <div class="text-xs text-gray-500">Pre-configured monitoring</div>
                </div>
            </div>
            <div class="space-y-2 mb-3">
                <div class="h-12 bg-gradient-to-r from-secondary-500/10 to-secondary-500/5 rounded border border-secondary-500/20 flex items-center px-3">
                    <span class="text-xs text-gray-400">Pod CPU & Memory</span>
                </div>
                <div class="h-12 bg-gradient-to-r from-primary-500/10 to-primary-500/5 rounded border border-primary-500/20 flex items-center px-3">
                    <span class="text-xs text-gray-400">Network I/O</span>
                </div>
            </div>
            <div class="flex items-center justify-between text-xs text-gray-500">
                <span class="flex items-center gap-1">
                    <span class="w-1.5 h-1.5 rounded-full bg-secondary-500"></span>
                    8 panels
                </span>
                <button class="px-2 py-1 bg-white/5 rounded hover:bg-white/10 text-white">Use template</button>
            </div>
        </div>
        
        <!-- Background Card (blurred) -->
        <div class="absolute top-10 left-10 right-10 bottom-10 bg-white/5 border border-white/5 rounded-lg -z-10 blur-sm transform -rotate-2 scale-95 opacity-50"></div>
      </div>
    </div>
  </div>
</section>
