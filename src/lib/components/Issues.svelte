<section class="py-24 overflow-hidden">
  <div class="max-w-[1200px] mx-auto px-6 mb-16">
    <div class="flex items-center gap-2 text-primary-500 mb-4 text-sm font-medium">
        <svg viewBox="0 0 16 16" class="w-4 h-4 fill-current">
            <path d="M8 1a7 7 0 1 0 0 14A7 7 0 0 0 8 1zM7 4.5a.5.5 0 0 1 1 0v3.793l1.854 1.853a.5.5 0 0 1-.708.708l-2-2A.5.5 0 0 1 7 8.5v-4z"/>
        </svg>
        Alerting and incident detection
    </div>
    <h2 class="text-4xl md:text-5xl font-medium mb-6">Context-rich alerts<br />when you need them</h2>
    <p class="text-xl text-gray-400 max-w-2xl">
      <strong class="text-white">Intelligent alerting that reduces noise.</strong> Get notified via email, Slack, or your preferred tools with full context and recommended actions.
    </p>
  </div>

  <!-- Large 3D Interface Mockup -->
  <div class="relative w-full h-[800px] flex items-center justify-center -mt-20">
    <div class="absolute inset-0 bg-gradient-to-b from-transparent via-transparent to-black pointer-events-none z-10"></div>
    
    <div class="perspective-[2000px] w-full max-w-[1400px]">
        <div class="relative transform rotate-x-20 rotate-y-10 rotate-z-[-5deg] scale-90 origin-center translate-y-20">
            <!-- Main Board Layer -->
            <div class="bg-[#0e1012] border border-white/10 rounded-xl shadow-2xl p-6 w-[1200px] h-[800px] relative">
                <!-- Header -->
                <div class="flex items-center gap-8 mb-8 border-b border-white/5 pb-4">
                    <div class="text-white font-medium">Active Alerts</div>
                    <div class="text-gray-500">Resolved</div>
                    <div class="text-gray-500">Silenced</div>
                </div>

                <!-- Alerts List -->
                <div class="space-y-4">
                    <!-- Alert 1 -->
                    <div class="flex items-center gap-4 p-4 bg-white/[0.02] border border-white/5 rounded-lg hover:bg-white/[0.04] transition-colors group">
                        <div class="w-4 h-4 border border-primary-500 rounded-full"></div>
                        <div class="text-gray-500 font-mono text-sm">2 min ago</div>
                        <div class="text-white font-medium flex-1">High memory usage on payment-service</div>
                        <div class="flex items-center gap-2">
                            <span class="px-2 py-1 bg-primary-500/10 text-primary-400 rounded text-xs border border-primary-500/20">Critical</span>
                            <div class="w-6 h-6 rounded-full bg-primary-500"></div>
                        </div>
                    </div>

                    <!-- Alert 2 (Active/Selected) -->
                    <div class="relative transform translate-x-10 -translate-y-2 z-20">
                        <div class="absolute -inset-1 bg-secondary-500/20 blur-xl rounded-lg"></div>
                        <div class="flex items-center gap-4 p-6 bg-[#1a1c1e] border border-secondary-500/30 rounded-lg shadow-2xl relative">
                            <div class="w-5 h-5 bg-secondary-500 rounded-full flex items-center justify-center">
                                <svg viewBox="0 0 12 12" class="w-3 h-3 fill-white"><path d="M6 1a5 5 0 1 0 0 10A5 5 0 0 0 6 1zM5 3h2v3H5V3zm0 4h2v2H5V7z"/></svg>
                            </div>
                            <div class="text-secondary-400 font-mono text-sm">5 min ago</div>
                            <div class="text-white text-lg font-medium flex-1">API latency spike detected</div>
                            <div class="flex items-center gap-2">
                                <span class="px-2 py-1 bg-secondary-500/10 rounded text-xs text-secondary-400 border border-secondary-500/20">p95: 2.4s</span>
                                <div class="w-8 h-8 rounded-full bg-gray-700 border border-white/10"></div>
                            </div>
                        </div>
                    </div>

                    <!-- Alert 3 -->
                    <div class="flex items-center gap-4 p-4 bg-white/[0.02] border border-white/5 rounded-lg hover:bg-white/[0.04] transition-colors opacity-60">
                         <div class="w-4 h-4 border border-gray-600 rounded-full"></div>
                        <div class="text-gray-500 font-mono text-sm">12 min ago</div>
                        <div class="text-gray-400 font-medium flex-1">Database connection pool near capacity</div>
                        <div class="flex items-center gap-2">
                             <span class="px-2 py-1 bg-white/5 rounded text-xs text-gray-500 border border-white/5">Warning</span>
                            <div class="w-6 h-6 rounded-full bg-gray-800"></div>
                        </div>
                    </div>
                    
                     <!-- Alert 4 -->
                    <div class="flex items-center gap-4 p-4 bg-white/[0.02] border border-white/5 rounded-lg hover:bg-white/[0.04] transition-colors opacity-40">
                         <div class="w-4 h-4 border border-gray-600 rounded-full"></div>
                        <div class="text-gray-500 font-mono text-sm">18 min ago</div>
                        <div class="text-gray-400 font-medium flex-1">Increased error rate in auth-service</div>
                        <div class="flex items-center gap-2">
                             <span class="px-2 py-1 bg-white/5 rounded text-xs text-gray-500 border border-white/5">Warning</span>
                            <div class="w-6 h-6 rounded-full bg-gray-800"></div>
                        </div>
                    </div>
                </div>
            </div>
            
            <!-- Floating Elements / Depth Layers -->
            <div class="absolute top-20 right-20 w-64 p-4 bg-[#1a1c1e]/90 backdrop-blur-md border border-white/10 rounded-lg shadow-2xl transform translate-z-20 rotate-y-[-10deg]">
                <div class="text-xs text-gray-500 mb-2 flex items-center gap-2">
                    <span class="w-2 h-2 rounded-full bg-primary-500 animate-pulse"></span>
                    Firing
                </div>
                <div class="flex items-center gap-2 mb-1">
                    <span class="text-gray-400 font-mono text-xs">just now</span>
                    <span class="text-white text-sm">Pod restart loop detected</span>
                </div>
                <div class="flex gap-2 mt-2">
                     <span class="px-1.5 py-0.5 bg-primary-500/10 text-primary-400 text-[10px] rounded border border-primary-500/20">kubernetes</span>
                     <span class="px-1.5 py-0.5 bg-primary-500/10 text-primary-400 text-[10px] rounded border border-primary-500/20">production</span>
                </div>
            </div>
        </div>
    </div>
  </div>
</section>

<style>
    .rotate-x-20 {
        transform: rotateX(20deg);
    }
    .rotate-y-10 {
        transform: rotateY(10deg);
    }
    .rotate-z-\[-5deg\] {
        transform: rotateZ(-5deg);
    }
    .translate-z-20 {
        transform: translateZ(50px);
    }
</style>
