<section class="py-24 border-t border-white/5">
  <div class="max-w-[1200px] mx-auto px-6">
    <div class="flex flex-col md:flex-row gap-16 items-center mb-24">
        <!-- Left Side Text -->
        <div class="md:w-1/3">
            <h2 class="text-4xl font-medium mb-6">OpenTelemetry-native<br />from day one</h2>
            <div class="space-y-6">
                <div class="pl-4 border-l-2 border-secondary-500">
                    <h3 class="text-lg font-medium text-white mb-1">Zero vendor lock-in</h3>
                    <p class="text-gray-500">Open standards, portable data</p>
                </div>
                <div class="pl-4 border-l-2 border-transparent hover:border-white/20 transition-colors cursor-pointer">
                    <h3 class="text-lg font-medium text-gray-400 hover:text-white transition-colors mb-1">Semantic conventions</h3>
                </div>
            </div>
        </div>

        <!-- Right Side Image -->
        <div class="md:w-2/3 w-full">
            <div class="bg-[#0e1012] border border-white/10 rounded-xl overflow-hidden shadow-2xl relative">
                <!-- Code Editor Mockup -->
                <div class="p-1 bg-[#1a1c1e] border-b border-white/5 flex items-center gap-2 px-4 h-10">
                    <div class="text-xs text-gray-500">instrumentation.ts</div>
                </div>
                <div class="p-8 min-h-[400px] bg-[#0b0d0e]">
                    <div class="max-w-md mx-auto">
                        <div class="w-12 h-12 bg-secondary-500/20 rounded-lg flex items-center justify-center mb-6 text-secondary-500">
                            <svg viewBox="0 0 24 24" class="w-6 h-6 fill-current"><path d="M9.4 16.6L4.8 12l4.6-4.6L8 6l-6 6 6 6 1.4-1.4zm5.2 0l4.6-4.6-4.6-4.6L16 6l6 6-6 6-1.4-1.4z"/></svg>
                        </div>
                        <h3 class="text-2xl font-medium mb-4">Simple integration</h3>
                        <p class="text-gray-400 leading-relaxed mb-6 relative font-mono text-xs">
                            <span class="text-secondary-400">import</span> &#123; <span class="text-white">Dash0</span> &#125; <span class="text-secondary-400">from</span> <span class="text-primary-400">'@dash0/opentelemetry'</span>;<br/><br/>
                            
                            <span class="text-secondary-400">const</span> <span class="text-white">sdk</span> = <span class="text-white">Dash0</span>.<span class="text-secondary-400">init</span>(&#123;<br/>
                            &nbsp;&nbsp;<span class="text-white">serviceName</span>: <span class="text-primary-400">'my-service'</span>,<br/>
                            &nbsp;&nbsp;<span class="text-white">endpoint</span>: <span class="text-primary-400">'https://dash0.com'</span><br/>
                            &#125;);<br/><br/>
                            
                            <span class="text-gray-600">// Auto-instrumentation enabled</span>
                            
                            <!-- Status Indicator -->
                            <span class="absolute top-0 right-0 flex items-center gap-1 bg-secondary-500/10 px-2 py-1 rounded border border-secondary-500/20">
                                <span class="w-1.5 h-1.5 bg-secondary-500 rounded-full animate-pulse"></span>
                                <span class="text-secondary-400 text-[10px]">Connected</span>
                            </span>
                        </p>
                        
                        <div class="space-y-2 text-xs text-gray-500">
                            <div class="flex items-center gap-2">
                                <svg viewBox="0 0 12 12" class="w-3 h-3 fill-secondary-500"><path d="M6 10a4 4 0 1 0 0-8 4 4 0 0 0 0 8zm-1.5-2.5l-1-1 1-1 3.5 3.5-1 1-2.5-2.5z"/></svg>
                                <span>Traces, logs, and metrics automatically collected</span>
                            </div>
                            <div class="flex items-center gap-2">
                                <svg viewBox="0 0 12 12" class="w-3 h-3 fill-secondary-500"><path d="M6 10a4 4 0 1 0 0-8 4 4 0 0 0 0 8zm-1.5-2.5l-1-1 1-1 3.5 3.5-1 1-2.5-2.5z"/></svg>
                                <span>No proprietary SDKs required</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- 4 Items Grid -->
    <div class="grid grid-cols-1 md:grid-cols-4 gap-8 pt-12 border-t border-white/5">
        <div>
            <div class="flex items-center gap-2 text-white font-medium mb-2">
                <svg viewBox="0 0 24 24" class="w-4 h-4 text-secondary-400 fill-current"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm1 15h-2v-6h2v6zm0-8h-2V7h2v2z"/></svg>
                Auto-instrumentation
            </div>
            <p class="text-sm text-gray-500 leading-relaxed">Automatic telemetry collection with zero code changes.</p>
        </div>
        <div>
            <div class="flex items-center gap-2 text-white font-medium mb-2">
                <svg viewBox="0 0 24 24" class="w-4 h-4 text-primary-400 fill-current"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-1 17.93c-3.95-.49-7-3.85-7-7.93 0-.62.08-1.21.21-1.79L9 15v1c0 1.1.9 2 2 2v1.93zm6.9-2.54c-.26-.81-1-1.39-1.9-1.39h-1v-3c0-.55-.45-1-1-1H8v-2h2c.55 0 1-.45 1-1V7h2c1.1 0 2-.9 2-2v-.41c2.93 1.19 5 4.06 5 7.41 0 2.08-.8 3.97-2.1 5.39z"/></svg>
                Kubernetes support
            </div>
            <p class="text-sm text-gray-500 leading-relaxed">Native integration with predefined cluster views.</p>
        </div>
        <div>
            <div class="flex items-center gap-2 text-white font-medium mb-2">
                <svg viewBox="0 0 24 24" class="w-4 h-4 text-secondary-400 fill-current"><path d="M14.43 10L12 2l-2.43 8H2l6.18 4.41L5.83 22 12 17.31 18.18 22l-2.35-7.59L22 10z"/></svg>
                Prometheus compatible
            </div>
            <p class="text-sm text-gray-500 leading-relaxed">Full PromQL support, not emulation.</p>
        </div>
        <div>
            <div class="flex items-center gap-2 text-white font-medium mb-2">
                <svg viewBox="0 0 24 24" class="w-4 h-4 text-primary-400 fill-current"><path d="M3.5 18.49l6-6.01 4 4L22 6.92l-1.41-1.41-7.09 7.97-4-4L2 16.99z"/></svg>
                Configuration as Code
            </div>
            <p class="text-sm text-gray-500 leading-relaxed">ClickOps is a choice, not a necessity.</p>
        </div>
    </div>
  </div>
</section>
