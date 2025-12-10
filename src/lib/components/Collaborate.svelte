<section class="py-24 border-t border-white/5">
  <div class="max-w-[1200px] mx-auto px-6">
    <div class="flex items-center gap-2 text-secondary-400 mb-4 text-sm font-medium">
        <svg viewBox="0 0 16 16" class="w-4 h-4 fill-current">
            <path d="M11 2a1 1 0 0 1 .832.445l4 6a1 1 0 0 1 0 1.11l-4 6A1 1 0 0 1 11 16H5a1 1 0 0 1-.832-.445l-4-6a1 1 0 0 1 0-1.11l4-6A1 1 0 0 1 5 2h6z"/>
        </svg>
        Integrations and ecosystem
    </div>
    
    <div class="flex flex-col md:flex-row justify-between items-end mb-16 gap-8">
        <h2 class="text-4xl md:text-5xl font-medium max-w-xl">Works with your entire stack</h2>
        <p class="text-xl text-gray-400 max-w-md">
            Pre-built integrations for your technology stack. One-click setup with no customization required. Kubernetes, Prometheus, cloud providers, and more.
        </p>
    </div>

    <!-- Cards Grid -->
    <div class="grid grid-cols-1 md:grid-cols-4 gap-6">
        <!-- Card 1: Kubernetes -->
        <div class="group relative bg-[#0e1012] border border-white/10 rounded-xl overflow-hidden h-[400px] hover:bg-white/[0.02] transition-colors">
            <div class="p-6 h-full flex flex-col">
                <div class="flex-1 relative flex items-center justify-center">
                    <!-- K8s Icon Mockup -->
                    <div class="w-32 h-32 rounded-lg bg-secondary-500/10 border border-secondary-500/20 flex items-center justify-center transform rotate-2 group-hover:rotate-0 transition-transform duration-500">
                        <svg viewBox="0 0 24 24" class="w-16 h-16 text-secondary-400 fill-current">
                            <path d="M12 2L2 7v10l10 5 10-5V7L12 2zm0 2.18L19.82 8 12 11.82 4.18 8 12 4.18zM4 9.68l7 3.5v7.64l-7-3.5V9.68zm16 0v7.64l-7 3.5v-7.64l7-3.5z"/>
                        </svg>
                    </div>
                    
                    <div class="absolute bottom-4 left-4 right-4 bg-[#0b0d0e] rounded-lg border border-white/5 p-3 text-xs shadow-xl">
                        <div class="flex items-center gap-2 mb-2">
                            <div class="w-2 h-2 rounded-full bg-secondary-500"></div>
                            <span class="text-gray-400">Auto-discovery enabled</span>
                        </div>
                        <div class="flex items-center gap-2 text-white text-[10px]">
                            <span class="px-1.5 py-0.5 bg-secondary-500/10 rounded border border-secondary-500/20">12 pods</span>
                            <span class="px-1.5 py-0.5 bg-secondary-500/10 rounded border border-secondary-500/20">3 services</span>
                        </div>
                    </div>
                </div>
                
                <div class="mt-auto">
                    <div class="text-xs text-gray-500 mb-1">Kubernetes</div>
                    <h3 class="text-lg font-medium text-white mb-1">Native cluster monitoring</h3>
                    <div class="flex justify-end">
                         <span class="text-xl text-gray-600 group-hover:text-white transition-colors">+</span>
                    </div>
                </div>
            </div>
        </div>

        <!-- Card 2: Prometheus -->
        <div class="group relative bg-[#0e1012] border border-white/10 rounded-xl overflow-hidden h-[400px] hover:bg-white/[0.02] transition-colors">
            <div class="p-6 h-full flex flex-col">
                <div class="flex-1 relative overflow-hidden flex items-center justify-center">
                    <!-- PromQL Query Mockup -->
                    <div class="w-full">
                        <div class="bg-[#1a1c1e] rounded-lg border border-white/5 p-4 mb-3">
                            <div class="font-mono text-xs text-secondary-400 mb-2">
                                rate(http_requests_total[5m])
                            </div>
                            <div class="h-16 flex items-end gap-1">
                                {#each [30, 45, 35, 55, 40, 60, 50, 65, 55, 70] as height}
                                <div class="flex-1 bg-primary-500/50 rounded-t" style="height: {height}%"></div>
                                {/each}
                            </div>
                        </div>
                        
                        <div class="space-y-2 text-xs">
                            <div class="flex items-center gap-2 text-gray-400">
                                <svg viewBox="0 0 12 12" class="w-3 h-3 fill-secondary-500"><path d="M6 10a4 4 0 1 0 0-8 4 4 0 0 0 0 8zm-1.5-2.5l-1-1 1-1 3.5 3.5-1 1-2.5-2.5z"/></svg>
                                <span>Full PromQL support</span>
                            </div>
                            <div class="flex items-center gap-2 text-gray-400">
                                <svg viewBox="0 0 12 12" class="w-3 h-3 fill-secondary-500"><path d="M6 10a4 4 0 1 0 0-8 4 4 0 0 0 0 8zm-1.5-2.5l-1-1 1-1 3.5 3.5-1 1-2.5-2.5z"/></svg>
                                <span>Alertmanager integration</span>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div class="mt-auto">
                    <div class="text-xs text-gray-500 mb-1">Prometheus</div>
                    <h3 class="text-lg font-medium text-white mb-1">Native PromQL, not emulation</h3>
                    <div class="flex justify-end">
                         <span class="text-xl text-gray-600 group-hover:text-white transition-colors">+</span>
                    </div>
                </div>
            </div>
        </div>

        <!-- Card 3: Slack/Notifications -->
        <div class="group relative bg-[#0e1012] border border-white/10 rounded-xl overflow-hidden h-[400px] hover:bg-white/[0.02] transition-colors">
            <div class="p-6 h-full flex flex-col">
                <div class="flex-1 relative flex items-center justify-center">
                    <!-- Notification Mockup -->
                    <div class="w-full space-y-3">
                        <div class="bg-[#1a1c1e] rounded-lg border border-primary-500/20 p-3 shadow-lg transform -rotate-1 group-hover:rotate-0 transition-transform duration-500">
                            <div class="flex items-center gap-2 mb-2">
                                <div class="w-4 h-4 rounded bg-primary-500/20 flex items-center justify-center">
                                    <svg viewBox="0 0 12 12" class="w-2 h-2 fill-primary-500"><path d="M6 1a5 5 0 1 0 0 10A5 5 0 0 0 6 1zM5 3h2v3H5V3zm0 4h2v2H5V7z"/></svg>
                                </div>
                                <span class="text-white text-xs font-medium">Dash0 Alert</span>
                            </div>
                            <div class="text-[10px] text-gray-400">
                                🔴 High latency detected in payment-service
                            </div>
                        </div>
                        
                        <div class="bg-[#1a1c1e] rounded-lg border border-white/5 p-3 opacity-60">
                            <div class="flex items-center gap-2 mb-2">
                                <div class="w-4 h-4 rounded bg-secondary-500/20 flex items-center justify-center">
                                    <svg viewBox="0 0 12 12" class="w-2 h-2 fill-secondary-500"><path d="M6 10a4 4 0 1 0 0-8 4 4 0 0 0 0 8zm-1.5-2.5l-1-1 1-1 3.5 3.5-1 1-2.5-2.5z"/></svg>
                                </div>
                                <span class="text-white text-xs font-medium">Dash0</span>
                            </div>
                            <div class="text-[10px] text-gray-400">
                                ✅ All systems operational
                            </div>
                        </div>
                    </div>
                </div>

                <div class="mt-auto">
                    <div class="text-xs text-gray-500 mb-1">Notifications</div>
                    <h3 class="text-lg font-medium text-white mb-1">Alerts via Slack, email, or webhooks</h3>
                    <div class="flex justify-end">
                         <span class="text-xl text-gray-600 group-hover:text-white transition-colors">></span>
                    </div>
                </div>
            </div>
        </div>
        
        <!-- Card 4: Cloud Providers -->
        <div class="group relative bg-[#0e1012] border border-white/10 rounded-xl overflow-hidden h-[400px] hover:bg-white/[0.02] transition-colors">
             <div class="p-6 h-full flex flex-col">
                <div class="flex-1 relative flex items-center justify-center">
                    <div class="w-32 h-32 rounded-full border border-white/10 flex items-center justify-center relative">
                        <div class="absolute inset-0 border border-white/5 rounded-full animate-ping opacity-20"></div>
                        <div class="w-24 h-24 rounded-full bg-white/5 flex items-center justify-center">
                            <svg viewBox="0 0 24 24" class="w-8 h-8 text-white fill-current opacity-50">
                                <path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-1 17.93c-3.95-.49-7-3.85-7-7.93 0-.62.08-1.21.21-1.79L9 15v1c0 1.1.9 2 2 2v1.93zm6.9-2.54c-.26-.81-1-1.39-1.9-1.39h-1v-3c0-.55-.45-1-1-1H8v-2h2c.55 0 1-.45 1-1V7h2c1.1 0 2-.9 2-2v-.41c2.93 1.19 5 4.06 5 7.41 0 2.08-.8 3.97-2.1 5.39z"/>
                            </svg>
                        </div>
                        <div class="absolute top-0 right-0 w-8 h-8 bg-[#1a1c1e] border border-white/10 rounded flex items-center justify-center text-[10px] text-gray-400">AWS</div>
                        <div class="absolute bottom-0 left-0 w-8 h-8 bg-[#1a1c1e] border border-white/10 rounded flex items-center justify-center text-[10px] text-gray-400">GCP</div>
                        <div class="absolute top-1/2 left-0 -translate-y-1/2 w-8 h-8 bg-[#1a1c1e] border border-white/10 rounded flex items-center justify-center text-[10px] text-gray-400">Azure</div>
                    </div>
                </div>
                
                <div class="mt-auto">
                    <div class="text-xs text-gray-500 mb-1">Cloud Providers</div>
                    <h3 class="text-lg font-medium text-white mb-1">Monitor AWS, GCP, and Azure resources</h3>
                    <div class="flex justify-end">
                         <span class="text-xl text-gray-600 group-hover:text-white transition-colors">></span>
                    </div>
                </div>
            </div>
        </div>
    </div>
    
    <!-- Navigation Buttons -->
    <div class="flex justify-center gap-4 mt-12">
        <button class="w-10 h-10 rounded-full border border-white/10 flex items-center justify-center hover:bg-white/5 transition-colors" aria-label="Previous">
            <svg viewBox="0 0 24 24" class="w-4 h-4 fill-white"><path d="M15.41 7.41L14 6l-6 6 6 6 1.41-1.41L10.83 12z"/></svg>
        </button>
        <button class="w-10 h-10 rounded-full border border-white/10 flex items-center justify-center hover:bg-white/5 transition-colors" aria-label="Next">
            <svg viewBox="0 0 24 24" class="w-4 h-4 fill-white"><path d="M10 6L8.59 7.41 13.17 12l-4.58 4.59L10 18l6-6z"/></svg>
        </button>
    </div>
  </div>
</section>
