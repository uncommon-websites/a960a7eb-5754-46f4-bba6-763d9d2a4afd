<section class="py-24 border-t border-white/5">
  <div class="max-w-[1200px] mx-auto px-6">
    <div class="mb-16">
      <div class="flex items-center gap-2 text-primary-400 mb-4 text-sm font-medium">
        <svg viewBox="0 0 16 16" class="w-4 h-4 fill-current">
            <path d="M8 1a1 1 0 0 1 1 1v2.586l1.707-1.707a1 1 0 0 1 1.414 1.414L10.414 6H13a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1h-2.586l1.707 1.707a1 1 0 0 1-1.414 1.414L9 10.414V13a1 1 0 0 1-2 0v-2.586l-1.707 1.707a1 1 0 0 1-1.414-1.414L5.586 9H3a1 1 0 0 1-1-1V6a1 1 0 0 1 1-1h2.586L3.879 3.293a1 1 0 0 1 1.414-1.414L7 3.586V2a1 1 0 0 1 1-1z"/>
        </svg>
        Artificial Intelligence
      </div>
      <h2 class="text-4xl md:text-5xl font-medium mb-6">AI-powered observability</h2>
      <p class="text-xl text-gray-400 max-w-2xl">
        <strong class="text-white">The best AI feature is the one you love without knowing it's AI.</strong> Dash0 uses AI to reduce repetitive work, enhance telemetry safely with no hallucinations, and accelerate root cause analysis.
      </p>
      <div class="mt-8">
        <button class="bg-white/10 hover:bg-white/20 text-white px-4 py-2 rounded-full text-sm font-medium transition-colors border border-white/5">
            Learn more >
        </button>
      </div>
    </div>

    <!-- AI Interface Mockup -->
    <div class="relative bg-[#0e1012] border border-white/10 rounded-xl overflow-hidden shadow-2xl mb-24">
        <div class="p-8 md:p-12 min-h-[400px] flex flex-col items-center justify-center">
            <!-- Mockup of AI Triage -->
            <div class="w-full max-w-2xl bg-[#1a1c1e] rounded-lg border border-white/10 shadow-2xl overflow-hidden">
                <div class="p-4 border-b border-white/5 flex items-center justify-between">
                    <div class="flex items-center gap-2">
                        <div class="w-2 h-2 rounded-full bg-primary-500 animate-pulse"></div>
                        <span class="text-sm text-white font-medium">AI Triage Analysis</span>
                    </div>
                    <span class="text-xs text-gray-500">Real-time</span>
                </div>
                <div class="p-4">
                    <div class="mb-4">
                        <div class="text-xs text-gray-500 mb-2">Detected Anomaly</div>
                        <div class="flex items-center gap-2 text-sm text-white mb-2">
                            <span class="px-2 py-0.5 bg-primary-500/10 text-primary-400 rounded border border-primary-500/20">High Priority</span>
                            <span>API latency spike detected</span>
                        </div>
                        <div class="text-xs text-gray-400">Service: payment-gateway • p95 latency: 2.4s (↑340%)</div>
                    </div>
                    
                    <div class="bg-white/5 rounded border border-white/5 p-3 mb-3">
                        <div class="text-xs text-secondary-400 mb-2 flex items-center gap-1">
                            <svg viewBox="0 0 16 16" class="w-3 h-3 fill-current"><path d="M8 1a1 1 0 0 1 1 1v2.586l1.707-1.707a1 1 0 0 1 1.414 1.414L10.414 6H13a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1h-2.586l1.707 1.707a1 1 0 0 1-1.414 1.414L9 10.414V13a1 1 0 0 1-2 0v-2.586l-1.707 1.707a1 1 0 0 1-1.414-1.414L5.586 9H3a1 1 0 0 1-1-1V6a1 1 0 0 1 1-1h2.586L3.879 3.293a1 1 0 0 1 1.414-1.414L7 3.586V2a1 1 0 0 1 1-1z"/></svg>
                            AI Root Cause Analysis
                        </div>
                        <div class="text-xs text-gray-300 leading-relaxed">
                            Database connection pool exhaustion detected. Recent deployment increased concurrent requests by 3x without scaling connection limits. Recommend: increase max_connections from 100 to 300.
                        </div>
                    </div>
                    
                    <div class="flex gap-2">
                        <button class="px-3 py-1.5 bg-primary-500/10 text-primary-400 rounded text-xs hover:bg-primary-500/20 border border-primary-500/20">View traces</button>
                        <button class="px-3 py-1.5 bg-white/5 text-gray-400 rounded text-xs hover:bg-white/10">Create alert</button>
                        <button class="px-3 py-1.5 bg-white/5 text-gray-400 rounded text-xs hover:bg-white/10">Dismiss</button>
                    </div>
                </div>
            </div>
        </div>
        <!-- Glow effect -->
        <div class="absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 w-[600px] h-[300px] bg-primary-500/10 blur-[100px] pointer-events-none"></div>
    </div>

    <!-- Two Columns -->
    <div class="grid grid-cols-1 md:grid-cols-2 gap-12">
        <!-- Column 1 -->
        <div>
            <h3 class="text-2xl font-medium mb-3">Automated telemetry enrichment</h3>
            <p class="text-gray-400 mb-8">AI enhances your telemetry data with semantic context and correlations, making debugging faster and more intuitive.</p>
            
            <div class="bg-[#0e1012] border border-white/10 rounded-xl p-6 h-[300px] relative overflow-hidden group">
                <!-- Telemetry Enhancement Mockup -->
                <div class="space-y-3">
                    <div class="flex items-center gap-2 text-xs text-gray-500 uppercase tracking-wider mb-2">
                        <span class="w-2 h-2 rounded-full bg-secondary-500"></span> Semantic Context
                    </div>
                    <div class="p-3 bg-white/5 rounded border border-white/5 text-sm">
                        <div class="flex items-center gap-2 mb-2">
                            <span class="text-gray-400">Span:</span>
                            <span class="px-1.5 py-0.5 bg-secondary-500/10 text-secondary-400 rounded text-xs border border-secondary-500/20">POST /api/checkout</span>
                        </div>
                        <div class="p-3 bg-[#1a1c1e] rounded border border-white/5 mt-2">
                            <div class="text-xs text-gray-400 mb-1">AI-detected patterns</div>
                            <div class="text-xs text-gray-300 leading-relaxed mb-2">
                                Similar errors occurred 47 times in the last hour across 3 services. Common attribute: user_tier=premium
                            </div>
                            <div class="flex gap-1 flex-wrap">
                                <span class="px-1.5 py-0.5 bg-white/5 rounded text-[10px] text-gray-400">payment-service</span>
                                <span class="px-1.5 py-0.5 bg-white/5 rounded text-[10px] text-gray-400">user-service</span>
                                <span class="px-1.5 py-0.5 bg-white/5 rounded text-[10px] text-gray-400">billing-service</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- Column 2 -->
        <div>
            <h3 class="text-2xl font-medium mb-3">Intelligent alerting</h3>
            <p class="text-gray-400 mb-8">AI learns your system's baseline behavior and alerts only on genuine anomalies, reducing alert fatigue.</p>
            
            <div class="bg-[#0e1012] border border-white/10 rounded-xl p-6 h-[300px] relative overflow-hidden flex flex-col justify-center">
                <!-- Alert Intelligence Mockup -->
                <div class="space-y-3">
                    <div class="p-3 bg-primary-500/5 rounded border border-primary-500/20">
                        <div class="flex items-center gap-2 mb-2">
                            <div class="w-2 h-2 rounded-full bg-primary-500"></div>
                            <span class="text-sm text-white font-medium">Anomaly detected</span>
                            <span class="ml-auto text-xs text-gray-500">2 min ago</span>
                        </div>
                        <div class="text-xs text-gray-400 mb-2">
                            Error rate increased to 5.2% (baseline: 0.3%)
                        </div>
                        <div class="bg-[#0b0d0e] rounded p-2 text-xs text-gray-400 font-mono">
                            service.name: auth-api<br/>
                            http.status_code: 503<br/>
                            deployment.version: v2.4.1
                        </div>
                    </div>
                    
                    <div class="p-3 bg-white/5 rounded border border-white/5 opacity-50">
                        <div class="flex items-center gap-2 mb-1">
                            <div class="w-2 h-2 rounded-full bg-gray-500"></div>
                            <span class="text-xs text-gray-400">Normal traffic spike suppressed</span>
                        </div>
                        <div class="text-[10px] text-gray-500">
                            AI detected expected pattern (weekend traffic)
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
  </div>
</section>
