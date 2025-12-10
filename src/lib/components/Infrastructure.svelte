<section class="py-24 border-t border-white/5">
  <div class="max-w-[1200px] mx-auto px-6">
    <div class="flex items-center gap-2 text-gray-500 mb-4 text-sm font-medium">
        <svg viewBox="0 0 16 16" class="w-4 h-4 fill-current">
            <path d="M7.75 2a.75.75 0 0 1 .75.75V7h4.25a.75.75 0 1 1 0 1.5H8.5v4.25a.75.75 0 1 1-1.5 0V8.5H2.75a.75.75 0 0 1 0-1.5H7V2.75A.75.75 0 0 1 7.75 2Z"/>
        </svg>
        Under the hood
    </div>
    
    <div class="grid grid-cols-1 md:grid-cols-2 gap-16">
        <!-- Left Column -->
        <div>
            <h2 class="text-4xl md:text-5xl font-medium mb-6">Enterprise-grade<br />observability</h2>
            <p class="text-xl text-gray-400 mb-16 leading-relaxed">
                Dash0 delivers world-class observability with the reliability and security that enterprises demand. Fast, scalable, and built on open standards.
            </p>
            
            <div class="space-y-12">
                <div class="group cursor-pointer">
                    <h3 class="text-lg font-medium text-white mb-2 group-hover:text-secondary-400 transition-colors">High-performance ingestion</h3>
                    <p class="text-gray-500 max-w-sm leading-relaxed">Handle millions of telemetry events per second with sub-100ms query response times.</p>
                </div>
                
                <div class="group cursor-pointer">
                    <h3 class="text-lg font-medium text-white mb-2 flex items-center gap-2 group-hover:text-secondary-400 transition-colors">
                        Enterprise security <span class="text-gray-600 text-sm">></span>
                    </h3>
                    <p class="text-gray-500 max-w-sm leading-relaxed">SOC 2 Type II certified with encryption at rest and in transit. GDPR compliant.</p>
                </div>
                
                <div class="group cursor-pointer">
                    <h3 class="text-lg font-medium text-white mb-2 group-hover:text-secondary-400 transition-colors">Built to scale</h3>
                    <p class="text-gray-500 max-w-sm leading-relaxed">From startups to enterprises. Trusted by Vercel, Porsche Digital, and Bechtle.</p>
                </div>
            </div>
            
            <div class="flex gap-8 mt-16 pt-16 border-t border-white/5">
                <div class="flex flex-col items-center gap-2 text-gray-500">
                    <div class="w-12 h-12 rounded-full border border-white/10 flex items-center justify-center">
                        <span class="text-[10px] font-bold">SOC2</span>
                    </div>
                    <span class="text-xs flex items-center gap-1">SOC 2 <svg viewBox="0 0 12 12" class="w-3 h-3 fill-current"><path d="M6 10a4 4 0 1 0 0-8 4 4 0 0 0 0 8zm-1.5-2.5l-1-1 1-1 3.5 3.5-1 1-2.5-2.5z"/></svg></span>
                </div>
                <div class="flex flex-col items-center gap-2 text-gray-500">
                    <div class="w-12 h-12 rounded-full border border-white/10 flex items-center justify-center">
                        <span class="text-[10px] font-bold">GDPR</span>
                    </div>
                    <span class="text-xs flex items-center gap-1">GDPR <svg viewBox="0 0 12 12" class="w-3 h-3 fill-current"><path d="M6 10a4 4 0 1 0 0-8 4 4 0 0 0 0 8zm-1.5-2.5l-1-1 1-1 3.5 3.5-1 1-2.5-2.5z"/></svg></span>
                </div>
                <div class="flex flex-col items-center gap-2 text-gray-500">
                    <div class="w-12 h-12 rounded-full border border-white/10 flex items-center justify-center">
                        <svg viewBox="0 0 24 24" class="w-6 h-6 fill-current"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-2 15l-5-5 1.41-1.41L10 14.17l7.59-7.59L19 8l-9 9z"/></svg>
                    </div>
                    <span class="text-xs flex items-center gap-1">OTel Native</span>
                </div>
            </div>
        </div>

        <!-- Right Column (Visual) -->
        <div class="relative h-full min-h-[600px] border-l border-white/5">
            <div class="absolute inset-0 bg-[radial-gradient(ellipse_at_center,_var(--tw-gradient-stops))] from-purple-900/10 via-transparent to-transparent pointer-events-none"></div>
            
            <!-- Grid Visualization -->
            <div class="absolute inset-0 overflow-hidden">
                <!-- Vertical Lines -->
                <div class="absolute left-1/4 top-0 bottom-0 w-[1px] bg-white/5"></div>
                <div class="absolute left-2/4 top-0 bottom-0 w-[1px] bg-white/5"></div>
                <div class="absolute left-3/4 top-0 bottom-0 w-[1px] bg-white/5"></div>
                
                <!-- Horizontal Lines -->
                <div class="absolute top-1/4 left-0 right-0 h-[1px] bg-white/5"></div>
                <div class="absolute top-2/4 left-0 right-0 h-[1px] bg-white/5"></div>
                <div class="absolute top-3/4 left-0 right-0 h-[1px] bg-white/5"></div>
                
                <!-- Nodes -->
                <div class="absolute top-1/4 left-1/4 -translate-x-1/2 -translate-y-1/2 w-2 h-2 bg-white/20 rounded-full"></div>
                <div class="absolute top-2/4 left-2/4 -translate-x-1/2 -translate-y-1/2 w-2 h-2 bg-white/20 rounded-full"></div>
                <div class="absolute top-3/4 left-3/4 -translate-x-1/2 -translate-y-1/2 w-2 h-2 bg-white/20 rounded-full"></div>
                
                <!-- Active Node -->
                <div class="absolute top-1/4 left-3/4 -translate-x-1/2 -translate-y-1/2">
                    <div class="w-3 h-3 bg-secondary-500 rounded-full shadow-[0_0_15px_rgba(6,182,212,0.5)]"></div>
                    <div class="absolute top-4 left-1/2 -translate-x-1/2 w-24 p-2 bg-[#1a1c1e] border border-white/10 rounded text-[10px] text-gray-400 text-center">
                        INGESTION
                    </div>
                </div>
                
                <div class="absolute top-2/4 left-1/4 -translate-x-1/2 -translate-y-1/2">
                    <div class="w-16 h-16 border border-white/10 bg-white/5 backdrop-blur-sm flex items-center justify-center text-xs text-secondary-400 font-mono">
                        2.4M/s
                    </div>
                </div>
            </div>
        </div>
    </div>
  </div>
</section>
