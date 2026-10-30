# asesoravidamujer MR
Estoy aquí para acompañarte en esta gran aventura de ser Mujer, obteniendo los mejores beneficios, protegiendo tu presente y tu futuro.
<!DOCTYPE html>
<html lang="es" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mariel Fuentes Lugo | Asesora Patrimonial - Vida Mujer</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts: Playfair Display & Plus Jakarta Sans -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,500;0,600;0,700;1,400&family=Plus+Jakarta+Sans:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <!-- Lucide Icons -->
    <script src="https://unpkg.com/lucide@latest"></script>
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        clay: {
                            50: '#FDFBF7',
                            100: '#F7F2E9',
                            200: '#EFE5D5',
                            300: '#E2D3BD'
                        },
                        terracotta: {
                            DEFAULT: '#C86D51',
                            dark: '#A85339',
                            light: '#E07A5F'
                        },
                        espresso: {
                            DEFAULT: '#2C1810',
                            light: '#4A2E23',
                            muted: '#6B4C3E'
                        },
                        sage: {
                            DEFAULT: '#81B29A',
                            dark: '#5D8B74',
                            light: '#E8F1EC'
                        },
                        sand: '#D4A373'
                    },
                    fontFamily: {
                        serif: ['Playfair Display', 'serif'],
                        sans: ['Plus Jakarta Sans', 'sans-serif']
                    }
                }
            }
        }
    </script>
    <style>
        body {
            font-family: 'Plus Jakarta Sans', sans-serif;
            background-color: #FDFBF7;
            color: #2C1810;
        }
        .font-serif {
            font-family: 'Playfair Display', serif;
        }
        .glass-card {
            background: rgba(255, 255, 255, 0.85);
            backdrop-filter: blur(12px);
            border: 1px solid rgba(200, 109, 81, 0.12);
        }
        .custom-shadow {
            box-shadow: 0 20px 40px -15px rgba(44, 24, 16, 0.07);
        }
        /* Hide scrollbars for clean UI */
        .no-scrollbar::-webkit-scrollbar {
            display: none;
        }
        .no-scrollbar {
            -ms-overflow-style: none;
            scrollbar-width: none;
        }
        .accent-gradient {
            background: linear-gradient(135deg, #C86D51 0%, #E07A5F 100%);
        }
        .soft-glow {
            box-shadow: 0 0 30px rgba(200, 109, 81, 0.18);
        }
    </style>
</head>
<body class="antialiased text-espresso bg-clay-50 selection:bg-terracotta selection:text-white">

    <!-- Header Navigation -->
    <header class="sticky top-0 z-40 w-full glass-card border-b border-clay-200/60 transition-all duration-300" id="navbar">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-20 flex items-center justify-between">
            <!-- Brand Logo -->
            <a href="#" class="flex items-center gap-3 group">
                <div class="w-10 h-10 rounded-full bg-terracotta/10 border border-terracotta/30 flex items-center justify-center text-terracotta font-serif font-bold text-xl group-hover:bg-terracotta group-hover:text-white transition-all duration-300">
                    M
                </div>
                <div class="flex flex-col">
                    <span class="font-serif font-bold text-lg leading-tight tracking-wide text-espresso">Mariel Fuentes Lugo</span>
                    <span class="text-xs text-terracotta font-medium tracking-wider uppercase">Asesora Patrimonial</span>
                </div>
            </a>

            <!-- Desktop Nav -->
            <nav class="hidden md:flex items-center gap-8 text-sm font-medium">
                <a href="#beneficios" class="hover:text-terracotta transition-colors py-1">Beneficios</a>
                <a href="#simulador" class="hover:text-terracotta transition-colors py-1">Simulador</a>
                <a href="#por-que-mariel" class="hover:text-terracotta transition-colors py-1">¿Por qué conmigo?</a>
                <a href="#faq" class="hover:text-terracotta transition-colors py-1">Preguntas Frecuentes</a>
            </nav>

            <!-- Header CTA -->
            <div class="hidden sm:flex items-center gap-3">
                <a href="mailto:mafuelugo@gmail.com" class="p-2.5 rounded-full bg-clay-100 text-espresso hover:text-terracotta hover:bg-clay-200 transition-all duration-300" title="Correo Electrónico">
                    <i data-lucide="mail" class="w-4 h-4"></i>
                </a>
                <a href="https://www.facebook.com/profile.php?id=100069204520004&locale=es_LA" target="_blank" rel="noopener noreferrer" class="p-2.5 rounded-full bg-clay-100 text-espresso hover:text-terracotta hover:bg-clay-200 transition-all duration-300" title="Página de Facebook">
                    <i data-lucide="facebook" class="w-4 h-4"></i>
                </a>
                <a href="https://wa.me/5215645550487?text=Hola%20Mariel,%20me%20gustar%C3%ADa%20recibir%20asesor%C3%ADa%20sobre%20el%20plan%20Vida%20Mujer" target="_blank" rel="noopener noreferrer" class="px-5 py-2.5 rounded-full accent-gradient text-white text-sm font-semibold hover:shadow-lg hover:shadow-terracotta/25 hover:-translate-y-0.5 transition-all duration-300 flex items-center gap-2">
                    <i data-lucide="message-circle" class="w-4 h-4"></i>
                    WhatsApp Directo
                </a>
            </div>

            <!-- Mobile Menu Button -->
<!-- ... existing code me... -->
        <!-- Mobile Navigation Menu -->
        <div id="mobileMenu" class="hidden md:hidden bg-clay-50/98 border-b border-clay-200 px-6 py-6 transition-all duration-300">
            <div class="flex flex-col gap-4 text-base font-medium">
                <a href="#beneficios" class="mobile-link py-2 border-b border-clay-100">Beneficios</a>
                <a href="#simulador" class="mobile-link py-2 border-b border-clay-100">Simulador Vida Mujer</a>
                <a href="#por-que-mariel" class="mobile-link py-2 border-b border-clay-100">¿Por qué conmigo?</a>
                <a href="#faq" class="mobile-link py-2 border-b border-clay-100">Preguntas Frecuentes</a>
                <a href="mailto:mafuelugo@gmail.com" class="mobile-link py-2 border-b border-clay-100 flex items-center gap-2 text-espresso">
                    <i data-lucide="mail" class="w-4 h-4 text-terracotta"></i>
                    mafuelugo@gmail.com
                </a>
                <a href="https://www.facebook.com/profile.php?id=100069204520004&locale=es_LA" target="_blank" rel="noopener noreferrer" class="mobile-link py-2 border-b border-clay-100 flex items-center gap-2 text-espresso">
                    <i data-lucide="facebook" class="w-4 h-4 text-terracotta"></i>
                    Visitar Facebook
                </a>
                <a href="https://wa.me/5215645550487?text=Hola%20Mariel,%20me%20gustar%C3%ADa%20recibir%20asesor%C3%ADa%20sobre%20el%20plan%20Vida%20Mujer" target="_blank" rel="noopener noreferrer" class="mobile-link mt-2 w-full text-center px-5 py-3 rounded-full accent-gradient text-white font-semibold flex items-center justify-center gap-2">
                    <i data-lucide="message-circle" class="w-4 h-4"></i>
                    Contactar por WhatsApp (+52 56 4555 0487)
                </a>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="relative pt-8 pb-20 lg:pt-16 lg:pb-28 overflow-hidden">
        <!-- Subtle background shapes -->
        <div class="absolute top-10 left-1/2 -translate-x-1/2 w-full max-w-7xl h-96 bg-gradient-to-tr from-terracotta/10 via-sand/10 to-transparent rounded-full blur-3xl -z-10 pointer-events-none"></div>

        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 lg:gap-8 items-center">
                
                <!-- Hero Content -->
                <div class="lg:col-span-7 flex flex-col items-start space-y-6 text-left">
                    <div class="inline-flex items-center gap-2 px-3.5 py-1.5 rounded-full bg-terracotta/10 border border-terracotta/20 text-terracotta text-xs sm:text-sm font-semibold tracking-wide">
                        <i data-lucide="shield-check" class="w-4 h-4"></i>
                        <span>Seguros Monterrey New York Life</span>
                    </div>

                    <h1 class="font-serif text-3xl sm:text-5xl lg:text-6xl font-bold text-espresso leading-tight">
                        Tu futuro, tu independencia y tu paz financiera tienen nombre: <span class="text-terracotta italic">Vida Mujer</span>.
                    </h1>

                    <p class="text-base sm:text-lg text-espresso-muted leading-relaxed max-w-2xl">
                        Hola, soy <strong class="text-espresso font-semibold">Mariel Fuentes Lugo</strong>, Asesora Patrimonial y Especialista en Protección Financiera Femenina. Te ayudo a construir un blindaje que protege tu salud, respalda tus proyectos y garantiza retornos de ahorro cada 2 años.
                    </p>

                    <!-- Key Pills -->
                    <div class="grid grid-cols-1 sm:grid-cols-3 gap-3 w-full pt-2">
                        <div class="flex items-center gap-2 p-3 rounded-2xl bg-white/70 border border-clay-200/80 shadow-sm">
                            <div class="w-8 h-8 rounded-full bg-sage/20 flex items-center justify-center text-sage-dark shrink-0">
                                <i data-lucide="coins" class="w-4 h-4"></i>
                            </div>
                            <span class="text-xs font-semibold text-espresso">Ahorro en UDIs / USD Garantizado</span>
                        </div>
                        <div class="flex items-center gap-2 p-3 rounded-2xl bg-white/70 border border-clay-200/80 shadow-sm">
                            <div class="w-8 h-8 rounded-full bg-terracotta/20 flex items-center justify-center text-terracotta shrink-0">
                                <i data-lucide="heart-pulse" class="w-4 h-4"></i>
                            </div>
                            <span class="text-xs font-semibold text-espresso">Protección ante Cáncer Femenino</span>
                        </div>
                        <div class="flex items-center gap-2 p-3 rounded-2xl bg-white/70 border border-clay-200/80 shadow-sm">
                            <div class="w-8 h-8 rounded-full bg-sand/30 flex items-center justify-center text-espresso shrink-0">
                                <i data-lucide="sparkles" class="w-4 h-4"></i>
                            </div>
                            <span class="text-xs font-semibold text-espresso">Liquidez desde el Año 5</span>
                        </div>
                    </div>

                    <!-- Call To Action Group -->
                    <div class="flex flex-col sm:flex-row items-stretch sm:items-center gap-4 w-full sm:w-auto pt-4">
                        <a href="#asesoria" class="px-8 py-4 rounded-full accent-gradient text-white font-semibold text-center hover:shadow-xl hover:shadow-terracotta/30 hover:-translate-y-0.5 transition-all duration-300 flex items-center justify-center gap-2 group">
                            <span>Agendar Asesoría Gratuita</span>
                            <i data-lucide="arrow-right" class="w-4 h-4 group-hover:translate-x-1 transition-transform"></i>
                        </a>
                        <a href="#simulador" class="px-8 py-4 rounded-full bg-white border border-terracotta/30 text-espresso font-semibold text-center hover:bg-clay-100 hover:border-terracotta transition-all duration-300 flex items-center justify-center gap-2">
                            <i data-lucide="calculator" class="w-4 h-4 text-terracotta"></i>
                            <span>Calcular Mi Plan</span>
                        </a>
                    </div>

                    <!-- Trust indicators -->
                    <div class="flex items-center gap-4 pt-4 border-t border-clay-200/80 w-full">
                        <div class="flex -space-x-2">
                            <div class="w-9 h-9 rounded-full bg-sand/40 border-2 border-white flex items-center justify-center text-xs font-bold text-espresso">MF</div>
                            <div class="w-9 h-9 rounded-full bg-terracotta/30 border-2 border-white flex items-center justify-center text-xs font-bold text-terracotta">SM</div>
                            <div class="w-9 h-9 rounded-full bg-sage/30 border-2 border-white flex items-center justify-center text-xs font-bold text-sage-dark">NY</div>
                        </div>
                        <div class="text-xs text-espresso-muted">
                            <span class="font-bold text-espresso block">Acompañamiento 100% Personalizado</span>
                            Sin presiones de venta, diseñado estrictamente a tus metas.
                        </div>
                    </div>
                </div>

                <!-- Profile Card / Visual Graphic -->
                <div class="lg:col-span-5 flex justify-center">
                    <div class="relative w-full max-w-md">
                        <!-- Decorative Frame Behind -->
                        <div class="absolute -inset-2 rounded-3xl bg-gradient-to-b from-terracotta/20 via-sand/20 to-sage/20 blur-xl"></div>
                        
                        <div class="relative bg-white p-6 sm:p-8 rounded-3xl shadow-xl border border-clay-200 flex flex-col items-center text-center">
                            <!-- Advisor Photo Placeholder Container -->
                            <div class="relative w-40 h-40 sm:w-48 sm:h-48 mb-6 rounded-full overflow-hidden border-4 border-clay-100 shadow-inner bg-gradient-to-br from-clay-100 to-clay-200 flex items-center justify-center">
                                <img src="https://images.unsplash.com/photo-1573496359142-b8d87734a5a2?auto=format&fit=crop&q=80&w=600" 
                                     alt="Mariel Fuentes Lugo - Asesora Patrimonial" 
                                     class="w-full h-full object-cover object-top"
                                     onerror="this.src='https://placehold.co/400x400/EFE5D5/2C1810?text=Mariel+Fuentes+Lugo'" />
                            </div>

                            <span class="px-3 py-1 rounded-full bg-sage/15 text-sage-dark text-xs font-bold tracking-wider uppercase mb-2">
                                Certified Financial Advisor
                            </span>
                            <h2 class="font-serif text-2xl font-bold text-espresso">Mariel Fuentes Lugo</h2>
                            <p class="text-xs text-terracotta font-semibold mb-4">Especialista en Protección Patrimonial y Vida Mujer</p>

                            <div class="w-full bg-clay-50 p-4 rounded-2xl border border-clay-200 text-left space-y-2 mb-6">
                                <div class="flex items-center gap-2 text-xs text-espresso font-medium">
                                    <i data-lucide="check-circle-2" class="w-4 h-4 text-terracotta shrink-0"></i>
                                    <span>Asesoría transparente en Gastos Médicos y Vida</span>
                                </div>
                                <div class="flex items-center gap-2 text-xs text-espresso font-medium">
                                    <i data-lucide="check-circle-2" class="w-4 h-4 text-terracotta shrink-0"></i>
                                    <span>Planes normados y respaldados por SMNYL</span>
                                </div>
                                <div class="flex items-center gap-2 text-xs text-espresso font-medium">
                                    <i data-lucide="check-circle-2" class="w-4 h-4 text-terracotta shrink-0"></i>
                                    <span>Estrategias adaptadas a tu presupuesto real</span>
                                </div>
                            </div>

                            <div class="flex flex-col gap-2.5 w-full">
                                <a href="https://wa.me/5215645550487?text=Hola%20Mariel,%20me%20gustar%C3%ADa%20recibir%20asesor%C3%ADa%20sobre%20el%20plan%20Vida%20Mujer" target="_blank" rel="noopener noreferrer" class="w-full py-3 px-4 rounded-xl bg-emerald-700 hover:bg-emerald-800 text-white font-semibold text-sm transition-all duration-300 flex items-center justify-center gap-2 shadow-sm">
                                    <i data-lucide="message-circle" class="w-4 h-4"></i>
                                    WhatsApp: +52 56 4555 0487
                                </a>
                                <a href="mailto:mafuelugo@gmail.com" class="w-full py-2.5 px-4 rounded-xl bg-clay-100 hover:bg-clay-200 text-espresso font-semibold text-xs transition-all duration-300 flex items-center justify-center gap-2 border border-clay-200">
                                    <i data-lucide="mail" class="w-4 h-4 text-terracotta"></i>
                                    mafuelugo@gmail.com
                                </a>
                                <a href="https://www.facebook.com/profile.php?id=100069204520004&locale=es_LA" target="_blank" rel="noopener noreferrer" class="w-full py-2.5 px-4 rounded-xl bg-clay-100 hover:bg-clay-200 text-espresso font-semibold text-xs transition-all duration-300 flex items-center justify-center gap-2 border border-clay-200">
                                    <i data-lucide="facebook" class="w-4 h-4 text-terracotta"></i>
                                    Ver más información en Facebook
                                </a>
                            </div>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- Multi-Step Interactive Intake Form / Qualification Quiz -->
    <section id="asesoria" class="py-20 bg-clay-100/60 relative">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-10">
                <span class="text-terracotta font-semibold text-sm uppercase tracking-widest">Reserva tu Sesión 1 a 1</span>
                <h2 class="font-serif text-3xl sm:text-4xl font-bold text-espresso mt-2">Agenda tu Asesoría Patrimonial Gratuita</h2>
                <p class="text-espresso-muted mt-2 text-sm sm:text-base">
                    Completa este breve formulario (menos de 1 minuto) para personalizar la propuesta antes de nuestra videollamada.
                </p>
            </div>

            <!-- Quiz Container -->
            <div class="glass-card rounded-3xl p-6 sm:p-10 shadow-2xl border border-clay-200">
                
                <!-- Progress Bar -->
                <div class="mb-8">
                    <div class="flex justify-between items-center text-xs font-semibold text-espresso-muted mb-2">
                        <span id="stepIndicator">Paso 1 de 3</span>
                        <span id="stepPercentage">33% completado</span>
                    </div>
                    <div class="w-full h-2 bg-clay-200 rounded-full overflow-hidden">
                        <div id="progressBar" class="h-full accent-gradient w-1/3 transition-all duration-300"></div>
                    </div>
                </div>

                <form id="quizForm" onsubmit="handleQuizSubmit(event)">
                    
                    <!-- STEP 1: Priorities & Age -->
                    <div id="step1" class="space-y-6">
                        <h3 class="font-serif text-xl font-bold text-espresso">1. ¿Cuál es tu objetivo financiero principal hoy en día?</h3>
                        
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                            <label class="quiz-option p-4 rounded-2xl border border-clay-200 bg-white hover:border-terracotta cursor-pointer transition-all flex items-center gap-3">
                                <input type="radio" name="quizGoal" value="Garantizar mi ahorro a 20 años" checked class="accent-terracotta">
                                <span class="text-sm font-medium text-espresso">Garantizar mi ahorro a 20 años</span>
                            </label>

                            <label class="quiz-option p-4 rounded-2xl border border-clay-200 bg-white hover:border-terracotta cursor-pointer transition-all flex items-center gap-3">
                                <input type="radio" name="quizGoal" value="Contar con protección médica para padecimientos femeninos" class="accent-terracotta">
                                <span class="text-sm font-medium text-espresso">Protección para salud femenina</span>
                            </label>

                            <label class="quiz-option p-4 rounded-2xl border border-clay-200 bg-white hover:border-terracotta cursor-pointer transition-all flex items-center gap-3">
                                <input type="radio" name="quizGoal" value="Planificar maternidad o respaldo familiar" class="accent-terracotta">
                                <span class="text-sm font-medium text-espresso">Planificar mi maternidad / familia</span>
                            </label>

                            <label class="quiz-option p-4 rounded-2xl border border-clay-200 bg-white hover:border-terracotta cursor-pointer transition-all flex items-center gap-3">
                                <input type="radio" name="quizGoal" value="Crear un fondo de emergencias de alta liquidez" class="accent-terracotta">
                                <span class="text-sm font-medium text-espresso">Crear liquidez bienal constante</span>
                            </label>
                        </div>

                        <div class="pt-4">
                            <label class="block text-sm font-medium text-espresso mb-1">¿Qué edad tienes?</label>
                            <input type="number" id="quizAge" min="18" max="65" placeholder="Ej. 32" required class="w-full p-3.5 rounded-xl border border-clay-200 focus:outline-none focus:border-terracotta bg-white text-espresso">
                        </div>

                        <div class="flex justify-end pt-4">
                            <button type="button" onclick="goToStep(2)" class="px-8 py-3.5 rounded-full accent-gradient text-white font-semibold text-sm flex items-center gap-2">
                                <span>Siguiente</span>
                                <i data-lucide="arrow-right" class="w-4 h-4"></i>
                            </button>
                        </div>
                    </div>

                    <!-- STEP 2: Budget & Preferred Call Method -->
                    <div id="step2" class="space-y-6 hidden">
                        <h3 class="font-serif text-xl font-bold text-espresso">2. Capacidad de ahorro y preferencia de contacto</h3>

                        <div>
                            <label class="block text-sm font-medium text-espresso mb-2">¿Con qué rango de ahorro mensual te sentirías cómoda?</label>
                            <select id="quizBudgetRange" class="w-full p-3.5 rounded-xl border border-clay-200 focus:outline-none focus:border-terracotta bg-white text-espresso">
                                <option value="$2,000 - $3,500 MXN mensuales">$2,000 - $3,500 MXN mensuales</option>
                                <option value="$3,500 - $5,000 MXN mensuales" selected>$3,500 - $5,000 MXN mensuales</option>
                                <option value="$5,000 - $8,000 MXN mensuales">$5,000 - $8,000 MXN mensuales</option>
                                <option value="Más de $8,000 MXN mensuales">Más de $8,000 MXN mensuales</option>
                            </select>
                        </div>

                        <div>
                            <label class="block text-sm font-medium text-espresso mb-2">¿Cómo prefieres realizar tu primera asesoría de 20 minutos?</label>
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                                <label class="p-4 rounded-2xl border border-clay-200 bg-white hover:border-terracotta cursor-pointer transition-all flex items-center gap-3">
                                    <input type="radio" name="quizPlatform" value="Videollamada por Zoom" checked class="accent-terracotta">
                                    <span class="text-sm font-medium text-espresso flex items-center gap-2">
                                        <i data-lucide="video" class="w-4 h-4 text-terracotta"></i> Zoom Videollamada
                                    </span>
                                </label>
                                <label class="p-4 rounded-2xl border border-clay-200 bg-white hover:border-terracotta cursor-pointer transition-all flex items-center gap-3">
                                    <input type="radio" name="quizPlatform" value="Llamada o mensaje de WhatsApp" class="accent-terracotta">
                                    <span class="text-sm font-medium text-espresso flex items-center gap-2">
                                        <i data-lucide="phone-call" class="w-4 h-4 text-emerald-600"></i> WhatsApp / Audio
                                    </span>
                                </label>
                            </div>
                        </div>

                        <div class="flex justify-between pt-4">
                            <button type="button" onclick="goToStep(1)" class="px-6 py-3.5 rounded-full bg-clay-200 text-espresso font-semibold text-sm hover:bg-clay-300">
                                Regresar
                            </button>
                            <button type="button" onclick="goToStep(3)" class="px-8 py-3.5 rounded-full accent-gradient text-white font-semibold text-sm flex items-center gap-2">
                                <span>Siguiente</span>
                                <i data-lucide="arrow-right" class="w-4 h-4"></i>
                            </button>
                        </div>
                    </div>

                    <!-- STEP 3: Contact Details & Schedule -->
                    <div id="step3" class="space-y-6 hidden">
                        <h3 class="font-serif text-xl font-bold text-espresso">3. Tus datos de contacto</h3>

                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                            <div>
                                <label class="block text-xs font-semibold text-espresso uppercase mb-1">Nombre Completo *</label>
                                <input type="text" id="quizName" required placeholder="Ej. Ana Lucía Gómez" class="w-full p-3.5 rounded-xl border border-clay-200 focus:outline-none focus:border-terracotta bg-white text-espresso">
                            </div>
                            <div>
                                <label class="block text-xs font-semibold text-espresso uppercase mb-1">WhatsApp / Teléfono *</label>
                                <input type="tel" id="quizPhone" required placeholder="Ej. 55 1234 5678" class="w-full p-3.5 rounded-xl border border-clay-200 focus:outline-none focus:border-terracotta bg-white text-espresso">
                            </div>
                        </div>

                        <div>
                            <label class="block text-xs font-semibold text-espresso uppercase mb-1">Correo Electrónico *</label>
                            <input type="email" id="quizEmail" required placeholder="ejemplo@correo.com" class="w-full p-3.5 rounded-xl border border-clay-200 focus:outline-none focus:border-terracotta bg-white text-espresso">
                        </div>

                        <div>
                            <label class="block text-xs font-semibold text-espresso uppercase mb-1">Horario de preferencia para agendar</label>
                            <select id="quizSchedule" class="w-full p-3.5 rounded-xl border border-clay-200 focus:outline-none focus:border-terracotta bg-white text-espresso">
                                <option value="Mañana (9:00 AM - 1:00 PM)">Mañana (9:00 AM - 1:00 PM)</option>
                                <option value="Tarde (2:00 PM - 6:00 PM)" selected>Tarde (2:00 PM - 6:00 PM)</option>
                                <option value="Noche (6:00 PM - 8:00 PM)">Noche (6:00 PM - 8:00 PM)</option>
                            </select>
                        </div>

                        <div id="quizErrorMsg" class="hidden text-xs text-red-600 bg-red-50 p-3 rounded-lg border border-red-200">
                            Por favor completa todos los campos obligatorios.
                        </div>

                        <div class="flex justify-between pt-4">
                            <button type="button" onclick="goToStep(2)" class="px-6 py-3.5 rounded-full bg-clay-200 text-espresso font-semibold text-sm hover:bg-clay-300">
                                Regresar
                            </button>
                            <button type="submit" class="px-8 py-3.5 rounded-full accent-gradient text-white font-semibold text-sm shadow-lg hover:shadow-terracotta/30 flex items-center gap-2">
                                <i data-lucide="check" class="w-4 h-4"></i>
                                <span>Confirmar y Enviar Solicitud</span>
                            </button>
                        </div>
                    </div>

                </form>

                <!-- Thank You Screen State -->
                <div id="quizSuccess" class="hidden text-center py-8 space-y-4">
                    <div class="w-16 h-16 rounded-full bg-sage/20 text-sage-dark mx-auto flex items-center justify-center">
                        <i data-lucide="check-circle" class="w-10 h-10"></i>
                    </div>
                    <h3 class="font-serif text-2xl font-bold text-espresso">¡Gracias por tu solicitud!</h3>
                    <p class="text-sm text-espresso-muted max-w-md mx-auto">
                        He recibido tus datos correctamente. En un plazo menor a 24 horas hábiles me pondré en contacto contigo para confirmar la fecha y hora de tu sesión personalizada.
                    </p>
                    <div class="pt-4 flex flex-col sm:flex-row items-center justify-center gap-3">
                        <a href="https://wa.me/5215645550487?text=Hola%20Mariel,%20acabo%20de%20enviar%20mis%20datos%20en%20el%20sitio%20web" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-2 px-6 py-3 rounded-full bg-emerald-700 text-white font-semibold text-sm hover:bg-emerald-800 transition-colors">
                            <i data-lucide="message-circle" class="w-4 h-4"></i>
                            Acelerar respuesta en WhatsApp (+52 56 4555 0487)
                        </a>
                        <a href="mailto:mafuelugo@gmail.com" class="inline-flex items-center gap-2 px-6 py-3 rounded-full bg-clay-100 text-espresso font-semibold text-sm hover:bg-clay-200 transition-colors border border-clay-200">
                            <i data-lucide="mail" class="w-4 h-4 text-terracotta"></i>
                            Enviar correo
                        </a>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- FAQ Accordion Section -->
    <section id="faq" class="py-20 bg-white">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <span class="text-terracotta font-semibold text-sm uppercase tracking-widest">Resuelve tus Dudas</span>
                <h2 class="font-serif text-3xl sm:text-4xl font-bold text-espresso mt-2">Preguntas Frecuentes sobre Vida Mujer</h2>
                <p class="text-espresso-muted mt-2 text-sm sm:text-base">
                    Todo lo que necesitas saber antes de dar el paso con Mariel Fuentes Lugo.
                </p>
            </div>

            <div class="space-y-4">
                
                <!-- FAQ Item 1 -->
                <div class="border border-clay-200 rounded-2xl bg-clay-50 overflow-hidden">
                    <button onclick="toggleFaq(1)" class="w-full p-5 text-left font-serif font-bold text-lg text-espresso flex justify-between items-center gap-4 hover:text-terracotta transition-colors">
                        <span>¿Es un seguro de Gastos Médicos Mayores o de Vida?</span>
                        <i id="faqIcon-1" data-lucide="chevron-down" class="w-5 h-5 text-terracotta shrink-0 transition-transform duration-300"></i>
                    </button>
                    <div id="faqContent-1" class="hidden px-5 pb-5 text-sm text-espresso-muted leading-relaxed border-t border-clay-200/60 pt-3">
                        Vida Mujer es un <strong>seguro de ahorro con protección de vida y cobertura de padecimientos femeninos</strong>. No sustituye un seguro de Gastos Médicos Mayores (el cual paga directo al hospital por un siniestro o enfermedad), sino que te otorga una suma de dinero en efectivo directo a tu cuenta al diagnosticarse un padecimiento específico o cáncer femenino, dinero que puedes usar para lo que decidas sin comprobación de gastos hospitalarios.
                    </div>
                </div>

                <!-- FAQ Item 2 -->
                <div class="border border-clay-200 rounded-2xl bg-clay-50 overflow-hidden">
                    <button onclick="toggleFaq(2)" class="w-full p-5 text-left font-serif font-bold text-lg text-espresso flex justify-between items-center gap-4 hover:text-terracotta transition-colors">
                        <span>¿En qué moneda se contrata este plan? (UDIs o Dólares)</span>
                        <i id="faqIcon-2" data-lucide="chevron-down" class="w-5 h-5 text-terracotta shrink-0 transition-transform duration-300"></i>
                    </button>
                    <div id="faqContent-2" class="hidden px-5 pb-5 text-sm text-espresso-muted leading-relaxed border-t border-clay-200/60 pt-3">
                        Se contrata principalmente en <strong>UDIs (Unidades de Inversión)</strong> o Dólares americanos. La ventaja principal de las UDIs es que tu dinero nunca pierde poder adquisitivo frente a la inflación; el capital garantizado crece año con año al mismo ritmo que la economía mexicana.
                    </div>
                </div>

                <!-- FAQ Item 3 -->
                <div class="border border-clay-200 rounded-2xl bg-clay-50 overflow-hidden">
                    <button onclick="toggleFaq(3)" class="w-full p-5 text-left font-serif font-bold text-lg text-espresso flex justify-between items-center gap-4 hover:text-terracotta transition-colors">
                        <span>¿Qué pasa exactamente al cumplir los 20 años del plan?</span>
                        <i id="faqIcon-3" data-lucide="chevron-down" class="w-5 h-5 text-terracotta shrink-0 transition-transform duration-300"></i>
                    </button>
                    <div id="faqContent-3" class="hidden px-5 pb-5 text-sm text-espresso-muted leading-relaxed border-t border-clay-200/60 pt-3">
                        A los 20 años se cumple la maduración total del plan. En ese momento recibes el saldo restante acumulado de tu suma asegurada garantizada en una sola exhibición libre de impuestos (según las normativas fiscales vigentes) para disfrutar tu retiro, comprar un inmueble o financiar el proyecto de tus sueños.
                    </div>
                </div>

                <!-- FAQ Item 4 -->
                <div class="border border-clay-200 rounded-2xl bg-clay-50 overflow-hidden">
                    <button onclick="toggleFaq(4)" class="w-full p-5 text-left font-serif font-bold text-lg text-espresso flex justify-between items-center gap-4 hover:text-terracotta transition-colors">
                        <span>¿Qué requisitos necesito para contratar con Mariel?</span>
                        <i id="faqIcon-4" data-lucide="chevron-down" class="w-5 h-5 text-terracotta shrink-0 transition-transform duration-300"></i>
                    </button>
                    <div id="faqContent-4" class="hidden px-5 pb-5 text-sm text-espresso-muted leading-relaxed border-t border-clay-200/60 pt-3">
                        Solo necesitas: Tener entre 18 y 55 años de edad, contar con identificación oficial vigente (INE o Pasaporte), un comprobante de domicilio reciente y llenar un cuestionario médico y financiero de solicitud estándar que realizaremos en conjunto durante nuestra sesión.
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-espresso text-clay-100 py-16 border-t border-espresso-light">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 md:grid-cols-12 gap-8 pb-12 border-b border-espresso-light">
                
                <div class="md:col-span-5 space-y-4">
                    <div class="flex items-center gap-3">
                        <div class="w-10 h-10 rounded-full bg-terracotta text-white font-serif font-bold text-xl flex items-center justify-center">
                            M
                        </div>
                        <div>
                            <span class="font-serif font-bold text-lg text-white block">Mariel Fuentes Lugo</span>
                            <span class="text-xs text-terracotta-light uppercase tracking-wider">Asesora Patrimonial Certificada</span>
                        </div>
                    </div>
                    <p class="text-xs text-clay-300 leading-relaxed max-w-sm">
                        Especializada en consultoría patrimonial, blindaje financiero y planes de ahorro garantizados para la mujer con el respaldo de Seguros Monterrey New York Life.
                    </p>
                </div>

                <div class="md:col-span-3 space-y-3">
                    <h4 class="text-xs font-bold text-sand uppercase tracking-wider">Enlaces Rápidos</h4>
                    <ul class="space-y-2 text-xs text-clay-300">
                        <li><a href="#beneficios" class="hover:text-terracotta-light transition-colors">Beneficios Vida Mujer</a></li>
                        <li><a href="#simulador" class="hover:text-terracotta-light transition-colors">Simulador de Ahorro</a></li>
                        <li><a href="#por-que-mariel" class="hover:text-terracotta-light transition-colors">Sobre Mariel Fuentes</a></li>
                        <li><a href="#asesoria" class="hover:text-terracotta-light transition-colors">Agendar Cita</a></li>
                    </ul>
                </div>

                <div class="md:col-span-4 space-y-3">
                    <h4 class="text-xs font-bold text-sand uppercase tracking-wider">Contacto Directo</h4>
                    <div class="text-xs text-clay-300 space-y-2">
                        <a href="https://wa.me/5215645550487?text=Hola%20Mariel,%20me%20gustar%C3%ADa%20recibir%20asesor%C3%ADa%20sobre%20el%20plan%20Vida%20Mujer" target="_blank" rel="noopener noreferrer" class="flex items-center gap-2 hover:text-white transition-colors">
                            <i data-lucide="phone" class="w-4 h-4 text-emerald-500"></i>
                            <span>WhatsApp: +52 1 56 4555 0487</span>
                        </a>
                        <a href="mailto:mafuelugo@gmail.com" class="flex items-center gap-2 hover:text-white transition-colors">
                            <i data-lucide="mail" class="w-4 h-4 text-terracotta-light"></i>
                            <span>mafuelugo@gmail.com</span>
                        </a>
                        <a href="https://www.facebook.com/profile.php?id=100069204520004&locale=es_LA" target="_blank" rel="noopener noreferrer" class="flex items-center gap-2 hover:text-white transition-colors">
                            <i data-lucide="facebook" class="w-4 h-4 text-terracotta-light"></i>
                            <span>Página de Facebook Oficial</span>
                        </a>
                        <p class="flex items-center gap-2">
                            <i data-lucide="shield-check" class="w-4 h-4 text-sage"></i>
                            <span>Agente Apoderado Seguros Monterrey NYL</span>
                        </p>
                    </div>
                </div>

            </div>

            <!-- Legal Disclaimers -->
            <div class="pt-8 text-center sm:text-left text-[11px] text-clay-300 space-y-2">
                <p>
                    <strong>Aviso Legal y Descargo de Responsabilidad:</strong> Este sitio web es operado de manera independiente por Mariel Fuentes Lugo en su calidad de Asesora Patrimonial debidamente certificada. Las marcas "Seguros Monterrey New York Life" y "Vida Mujer" son marcas registradas de Seguros Monterrey New York Life, S.A. de C.V.
                </p>
                <p>
                    Las proyecciones numéricas mostradas en los simuladores son ejercicios ilustrativos basados en condiciones generales de la póliza en UDIs/pesos y están sujetas a la evaluación médica y financiera individual de cada solicitante.
                </p>
                <div class="pt-4 flex flex-col sm:flex-row justify-between items-center text-xs text-clay-300 gap-2">
                    <span>&copy; 2026 Mariel Fuentes Lugo — Todos los derechos reservados.</span>
                    <div class="flex gap-4">
                        <a href="#" class="hover:underline">Aviso de Privacidad</a>
                        <a href="#" class="hover:underline">Términos y Condiciones</a>
                    </div>
                </div>
            </div>
        </div>
    </footer>

    <!-- Floating WhatsApp Widget -->
    <a href="https://wa.me/5215645550487?text=Hola%20Mariel,%20me%20gustar%C3%ADa%20recibir%20informaci%C3%B3n%20sobre%20el%20plan%20Vida%20Mujer" 
       target="_blank" 
       rel="noopener noreferrer"
       class="fixed bottom-6 right-6 z-50 p-4 rounded-full bg-emerald-600 text-white shadow-2xl hover:bg-emerald-700 hover:scale-105 transition-all duration-300 flex items-center justify-center group"
       aria-label="Contactar por WhatsApp">
        <i data-lucide="message-circle" class="w-7 h-7"></i>
        <span class="max-w-0 overflow-hidden whitespace-nowrap group-hover:max-w-xs group-hover:ml-2 transition-all duration-500 ease-in-out text-xs font-bold">
            Chat Directo: +52 56 4555 0487
        </span>
    </a>

    <!-- Application Script -->
    <script>
        // Initialize Lucide Icons
        document.addEventListener('DOMContentLoaded', () => {
            lucide.createIcons();
            calculateSim(); // Initialize calculator defaults
        });

        // Mobile Menu Toggle Logic
        const mobileMenuBtn = document.getElementById('mobileMenuBtn');
        const mobileMenu = document.getElementById('mobileMenu');
        
        if (mobileMenuBtn && mobileMenu) {
            mobileMenuBtn.addEventListener('click', () => {
                mobileMenu.classList.toggle('hidden');
            });

            document.querySelectorAll('.mobile-link').forEach(link => {
                link.addEventListener('click', () => {
                    mobileMenu.classList.add('hidden');
                });
            });
        }

        // Active Goal State for Calculator
        let activeGoal = 'ahorro';
        function setGoal(goal) {
            activeGoal = goal;
            document.querySelectorAll('.goal-btn').forEach(btn => {
                btn.classList.remove('border-terracotta', 'bg-terracotta/10', 'text-terracotta', 'font-semibold');
                btn.classList.add('border-clay-200', 'text-espresso', 'font-medium');
            });
            const selectedBtn = document.getElementById(`goal-${goal}`);
            if (selectedBtn) {
                selectedBtn.classList.remove('border-clay-200', 'text-espresso', 'font-medium');
                selectedBtn.classList.add('border-terracotta', 'bg-terracotta/10', 'text-terracotta', 'font-semibold');
            }
            calculateSim();
        }

        // Age Slider Listener
        const ageInput = document.getElementById('ageInput');
        const ageDisplay = document.getElementById('ageDisplay');
        if (ageInput && ageDisplay) {
            ageInput.addEventListener('input', (e) => {
                ageDisplay.textContent = `${e.target.value} años`;
                calculateSim();
            });
        }

        // Live Calculator Logic
        function calculateSim() {
            const age = parseInt(document.getElementById('ageInput')?.value || 28);
            const budgetRadio = document.querySelector('input[name="budget"]:checked');
            const monthlyBudget = parseInt(budgetRadio ? budgetRadio.value : 2500);

            // Factor simulation based on monthly input
            let baseSuma = monthlyBudget * 300; 
            
            // Adjust factor according to age range
            if (age > 40) {
                baseSuma = baseSuma * 0.85;
            } else if (age < 25) {
                baseSuma = baseSuma * 1.15;
            }

            const sumaAseguradaFormatted = new Intl.NumberFormat('es-MX', { style: 'currency', currency: 'MXN', maximumFractionDigits: 0 }).format(baseSuma);
            const pagoBienalFormatted = new Intl.NumberFormat('es-MX', { style: 'currency', currency: 'MXN', maximumFractionDigits: 0 }).format(baseSuma * 0.05);

            // Update DOM Elements
            const sumaDisplay = document.getElementById('sumaAseguradaDisplay');
            const bienalDisplay = document.getElementById('pagoBienalValue');
            const saludDisplay = document.getElementById('saludValue');

            if (sumaDisplay) sumaDisplay.textContent = `${sumaAseguradaFormatted} MXN`;
            if (bienalDisplay) bienalDisplay.textContent = `${pagoBienalFormatted} MXN`;
            if (saludDisplay) saludDisplay.textContent = `${sumaAseguradaFormatted} MXN`;
        }

        // Smooth scroll to quiz from calculator
        function scrollToAssessment() {
            const formSection = document.getElementById('asesoria');
            if (formSection) {
                formSection.scrollIntoView({ behavior: 'smooth' });
            }
        }

        // Quiz Step Navigation Logic
        let currentStep = 1;
        function goToStep(step) {
            // Validation for step 1
            if (step === 2 && currentStep === 1) {
                const ageField = document.getElementById('quizAge');
                if (!ageField.value || ageField.value < 18 || ageField.value > 70) {
                    ageField.classList.add('border-red-500');
                    alert('Por favor introduce una edad válida.');
                    return;
                } else {
                    ageField.classList.remove('border-red-500');
                }
            }

            document.getElementById(`step${currentStep}`)?.classList.add('hidden');
            document.getElementById(`step${step}`)?.classList.remove('hidden');

            currentStep = step;

            // Update UI Indicators
            const stepIndicator = document.getElementById('stepIndicator');
            const stepPercentage = document.getElementById('stepPercentage');
            const progressBar = document.getElementById('progressBar');

            if (step === 1) {
                if (stepIndicator) stepIndicator.textContent = 'Paso 1 de 3';
                if (stepPercentage) stepPercentage.textContent = '33% completado';
                if (progressBar) progressBar.style.width = '33%';
            } else if (step === 2) {
                if (stepIndicator) stepIndicator.textContent = 'Paso 2 de 3';
                if (stepPercentage) stepPercentage.textContent = '66% completado';
                if (progressBar) progressBar.style.width = '66%';
            } else if (step === 3) {
                if (stepIndicator) stepIndicator.textContent = 'Paso 3 de 3';
                if (stepPercentage) stepPercentage.textContent = '100% completado';
                if (progressBar) progressBar.style.width = '100%';
            }
        }

        // Handle Form Submission
        function handleQuizSubmit(e) {
            e.preventDefault();

            const name = document.getElementById('quizName')?.value;
            const phone = document.getElementById('quizPhone')?.value;
            const email = document.getElementById('quizEmail')?.value;

            if (!name || !phone || !email) {
                document.getElementById('quizErrorMsg')?.classList.remove('hidden');
                return;
            }

            document.getElementById('quizErrorMsg')?.classList.add('hidden');
            
            // Hide step 3 form and reveal success screen
            document.getElementById('step3')?.classList.add('hidden');
            document.getElementById('quizSuccess')?.classList.remove('hidden');
        }

        // Accordion FAQ Toggle Logic
        function toggleFaq(id) {
            const content = document.getElementById(`faqContent-${id}`);
            const icon = document.getElementById(`faqIcon-${id}`);

            if (content) {
                content.classList.toggle('hidden');
            }
            if (icon) {
                icon.classList.toggle('rotate-180');
            }
        }
    </script>
</body>
</html>
