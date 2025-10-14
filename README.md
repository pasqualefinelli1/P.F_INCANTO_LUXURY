# pf-incanto
I Nostri Link 
<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>P.F. Incanto Luxury - I Nostri Profili</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body {
            box-sizing: border-box;
        }

        .gradient-bg {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
        }

        .card-hover {
            transition: all 0.3s ease;
        }

        .card-hover:hover {
            transform: translateY(-8px);
            box-shadow: 0 20px 40px rgba(0,0,0,0.15);
        }

        .vinted-gradient {
            background: linear-gradient(135deg, #09B1BA 0%, #00A8B5 100%);
        }

        .instagram-gradient {
            background: linear-gradient(135deg, #E4405F 0%, #C13584 50%, #833AB4 100%);
        }

        .pulse-animation {
            animation: pulse 2s infinite;
        }

        @keyframes pulse {
            0%, 100% { opacity: 1; }
            50% { opacity: 0.8; }
        }
    </style>
</head>
<body class="gradient-bg min-h-full">
    <div class="min-h-full py-12 px-4">
        <div class="max-w-4xl mx-auto">
            <!-- Header -->
            <div class="text-center mb-12">
                <!-- Logo Placeholder -->
                <div class="w-32 h-32 mx-auto mb-6 bg-white/20 rounded-2xl flex items-center justify-center backdrop-blur-sm border border-white/30">
                    <div class="text-center">
                        <div class="text-3xl font-bold text-white mb-1">PF</div>
                        <div class="text-xs text-white/80">LUXURY</div>
                    </div>
                </div>

                <h1 class="text-3xl md:text-4xl font-bold text-white mb-4">
                    P.F. Incanto Luxury
                </h1>
                <p class="text-lg text-white/90 mb-8">
                    Scopri i nostri profili per shopping di lusso e stile
                </p>
                <div class="w-24 h-1 bg-white/50 mx-auto rounded-full"></div>
            </div>

            <!-- Cards Container -->
            <div class="grid md:grid-cols-3 gap-6 mb-8">
                <!-- Instagram Card -->
                <div class="bg-white rounded-2xl p-6 shadow-xl card-hover">
                    <div class="text-center">
                        <div class="instagram-gradient w-16 h-16 rounded-2xl mx-auto mb-4 flex items-center justify-center">
                            <svg class="w-8 h-8 text-white" fill="currentColor" viewBox="0 0 24 24">
                                <path d="..."/>
                            </svg>
                        </div>
                        <h2 class="text-xl font-bold text-gray-800 mb-3">Instagram</h2>
                        <p class="text-gray-600 mb-3">@p_f_incanto_luxury</p>
                        <p class="text-xs text-gray-500 mb-4">Segui per le ultime novità</p>
                        <a href="https://www.instagram.com/p_f_incanto_luxury?igsh=YTRkODJlZjM0OTRt&utm_source=qr" 
                           target="_blank" 
                           rel="noopener noreferrer"
                           class="instagram-gradient text-white px-6 py-2 rounded-lg text-sm font-semibold hover:opacity-90 transition-all duration-300 inline-block">
                            Visita Instagram
                        </a>
                    </div>
                </div>

                <!-- TikTok Card -->
                <div class="bg-white rounded-2xl p-6 shadow-xl card-hover">
                    <div class="text-center">
                        <div class="bg-black w-16 h-16 rounded-2xl mx-auto mb-4 flex items-center justify-center">
                            <svg class="w-8 h-8 text-white" fill="currentColor" viewBox="0 0 24 24">
                                <path d="..."/>
                            </svg>
                        </div>
                        <h2 class="text-xl font-bold text-gray-800 mb-3">TikTok</h2>
                        <p class="text-gray-600 mb-3">@effeluxury2</p>
                        <p class="text-xs text-gray-500 mb-4">Video e contenuti esclusivi</p>
                        <a href="https://www.tiktok.com/@effeluxury2?_t=ZN-90PldzDsqxy&_r=1" 
                           target="_blank" 
                           rel="noopener noreferrer"
                           class="bg-black text-white px-6 py-2 rounded-lg text-sm font-semibold hover:bg-gray-800 transition-all duration-300 inline-block">
                            Visita TikTok
                        </a>
                    </div>
                </div>

                <!-- Vinted Cards -->
                <div class="space-y-4">
                    <div class="bg-white rounded-2xl p-4 shadow-xl card-hover">
                        <div class="text-center">
                            <div class="vinted-gradient w-12 h-12 rounded-xl mx-auto mb-3 flex items-center justify-center">
                                <svg class="w-6 h-6 text-white" fill="currentColor" viewBox="0 0 24 24">
                                    <path d="..."/>
                                </svg>
                            </div>
                            <h3 class="text-sm font-bold text-gray-800 mb-1">Vinted - fatypaky13</h3>
                            <p class="text-xs text-gray-500 mb-3">Profilo principale</p>
                            <a href="https://www.vinted.it/member/278612511-fatypaky13" 
                               target="_blank" 
                               rel="noopener noreferrer"
                               class="vinted-gradient text-white px-4 py-1.5 rounded-lg text-xs font-semibold hover:opacity-90 transition-all duration-300 inline-block">
                                Vai al Profilo
                            </a>
                        </div>
                    </div>

                    <div class="bg-white rounded-2xl p-4 shadow-xl card-hover">
                        <div class="text-center">
                            <div class="vinted-gradient w-12 h-12 rounded-xl mx-auto mb-3 flex items-center justify-center">
                                <svg class="w-6 h-6 text-white" fill="currentColor" viewBox="0 0 24 24">
                                    <path d="..."/>
                                </svg>
                            </div>
                            <h3 class="text-sm font-bold text-gray-800 mb-1">Vinted - pf146</h3>
                            <p class="text-xs text-gray-500 mb-3">Profilo secondario</p>
                            <a href="https://www.vinted.it/member/180808622-pf146" 
                               target="_blank" 
                               rel="noopener noreferrer"
                               class="vinted-gradient text-white px-4 py-1.5 rounded-lg text-xs font-semibold hover:opacity-90 transition-all duration-300 inline-block">
                                Vai al Profilo
                            </a>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Footer -->
            <div class="text-center">
                <div class="bg-white/10 backdrop-blur-sm rounded-2xl p-6">
                    <h3 class="text-xl font-semibold text-white mb-3">🛍️ Shopping di Qualità</h3>
                    <p class="text-white/80 text-sm leading-relaxed">
                        Trova articoli di lusso e di qualità sui nostri profili Vinted. 
                        Seguici su Instagram per rimanere aggiornato sulle ultime novità!
                    </p>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
