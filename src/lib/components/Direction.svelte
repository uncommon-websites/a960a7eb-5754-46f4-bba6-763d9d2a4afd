<section class="py-24 overflow-hidden">
  <div class="max-w-[1200px] mx-auto px-6 mb-16">
    <div class="flex items-center gap-2 text-secondary-400 mb-4 text-sm font-medium">
        <svg viewBox="0 0 16 16" class="w-4 h-4 fill-current">
            <path d="M2.5 13.5A.5.5 0 0 1 3 13h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5zM2 2h12v2H2V2zm0 3h12v2H2V5zm0 3h12v2H2V8z"/>
        </svg>
        Unified observability platform
    </div>
    <h2 class="text-4xl md:text-5xl font-medium mb-6">Complete system visibility</h2>
    <p class="text-xl text-gray-400 max-w-2xl">
      <strong class="text-white">Logs, metrics, and traces in one place.</strong> Dash0 centralizes all your telemetry data with OpenTelemetry semantic conventions for instant correlation and context.
    </p>
  </div>

  <!-- Data Flow Visualization -->
  <div class="relative w-full h-[600px] flex items-center justify-center bg-gradient-to-b from-transparent to-black/50">
    <div class="absolute inset-0 bg-[radial-gradient(ellipse_at_center,_var(--tw-gradient-stops))] from-secondary-900/10 via-transparent to-transparent pointer-events-none"></div>
    
    <div class="perspective-[1000px] w-full max-w-[1400px] px-6">
        <div class="relative transform rotate-x-20 scale-90 origin-center">
            <!-- Data Flow Grid -->
            <div class="grid grid-cols-12 gap-0 border-t border-white/10 h-[400px]">
                {#each [1,2,3,4,5,6,7,8,9,10,11,12] as col}
                    <div class="border-r border-white/5 h-full relative">
                        <span class="absolute -top-8 left-2 text-xs text-gray-600 font-mono">{col}:00</span>
                    </div>
                {/each}
            </div>

            <!-- Telemetry Streams -->
            <div class="absolute top-10 left-[10%] w-[30%] h-16 bg-secondary-500/10 border border-secondary-500/30 rounded-lg backdrop-blur-sm flex items-center px-4 shadow-[0_0_30px_rgba(6,182,212,0.1)] hover:bg-secondary-500/20 transition-colors cursor-pointer group">
                <div class="w-2 h-2 rounded-full bg-secondary-500 mr-3"></div>
                <span class="text-secondary-100 font-medium text-sm">Traces</span>
                <span class="ml-auto text-xs text-gray-500">2.4M spans/min</span>
                <div class="absolute -bottom-1 left-1/2 -translate-x-1/2 w-1 h-8 bg-gradient-to-b from-secondary-500/50 to-transparent"></div>
            </div>

            <div class="absolute top-32 left-[20%] w-[25%] h-16 bg-primary-500/10 border border-primary-500/30 rounded-lg backdrop-blur-sm flex items-center px-4 shadow-[0_0_30px_rgba(236,72,153,0.1)] hover:bg-primary-500/20 transition-colors cursor-pointer">
                <div class="w-2 h-2 rounded-full bg-primary-500 mr-3"></div>
                <span class="text-primary-100 font-medium text-sm">Logs</span>
                <span class="ml-auto text-xs text-gray-500">850k/min</span>
            </div>

            <div class="absolute top-32 left-[50%] w-[20%] h-16 bg-secondary-500/10 border border-secondary-500/30 rounded-lg backdrop-blur-sm flex items-center px-4 shadow-[0_0_30px_rgba(6,182,212,0.1)] hover:bg-secondary-500/20 transition-colors cursor-pointer">
                <div class="w-2 h-2 rounded-full bg-secondary-500 mr-3"></div>
                <span class="text-secondary-100 font-medium text-sm">Metrics</span>
                <span class="ml-auto text-xs text-gray-500">1.2M/min</span>
            </div>

            <div class="absolute top-56 left-[55%] w-[30%] h-16 bg-white/10 border border-white/30 rounded-lg backdrop-blur-sm flex items-center px-4 shadow-[0_0_30px_rgba(255,255,255,0.1)] hover:bg-white/20 transition-colors cursor-pointer">
                <div class="w-2 h-2 rounded-full bg-white mr-3"></div>
                <span class="text-white font-medium text-sm">Unified Dashboard</span>
                
                <!-- Connector Lines -->
                <div class="absolute top-1/2 -left-24 w-24 h-[1px] border-t border-dashed border-white/20"></div>
                <div class="absolute top-1/2 -left-24 w-2 h-2 rounded-full bg-white/20 -translate-y-1/2"></div>
            </div>
        </div>
    </div>
  </div>
</section>

<style>
    .rotate-x-20 {
        transform: perspective(1000px) rotateX(25deg) scale(0.95);
    }
</style>
