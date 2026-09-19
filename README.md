<!DOCTYPE html>
<html lang="es" class="dark">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Adriel Hernández Hernández - Perfil Profesional</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            darkMode: 'class',
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            50: '#f0fdf4',
                            500: '#10b981',
                            600: '#059669',
                            700: '#047857',
                            900: '#064e3b',
                        }
                    }
                }
            }
        }
    </script>
    <!-- Google Fonts Inter & FontAwesome -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        /* Custom scrollbar and subtle animations */
        ::-webkit-scrollbar {
            width: 8px;
        }
        ::-webkit-scrollbar-track {
            background: #0f172a;
        }
        ::-webkit-scrollbar-thumb {
            background: #334155;
            border-radius: 4px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #475569;
        }
        .glass-card {
            background: rgba(30, 41, 59, 0.7);
            backdrop-filter: blur(12px);
            border: 1px solid rgba(51, 65, 85, 0.5);
        }
        .gradient-text {
            background: linear-gradient(135deg, #38bdf8 0%, #818cf8 50%, #c084fc 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
    </style>
</head>
<body class="bg-slate-950 text-slate-100 font-sans antialiased min-h-screen selection:bg-emerald-500 selection:text-white">

    <!-- Top Floating Navbar -->
    <header class="sticky top-0 z-50 glass-card border-b border-slate-800/80 px-6 py-4">
        <div class="max-w-6xl mx-auto flex justify-between items-center">
            <div class="flex items-center space-x-3">
                <div class="w-10 h-10 rounded-xl bg-gradient-to-tr from-sky-500 to-indigo-600 flex items-center justify-center font-bold text-lg text-white shadow-lg shadow-sky-500/20">
                    AH
                </div>
                <div>
                    <span class="font-bold text-lg tracking-tight">Adriel Hernández</span>
                    <span class="block text-xs text-sky-400 font-medium">Software Developer & Tutor</span>
                </div>
            </div>
            <nav class="hidden md:flex items-center space-x-6 text-sm font-medium text-slate-300">
                <a href="#about" class="hover:text-sky-400 transition">Sobre mí</a>
                <a href="#skills" class="hover:text-sky-400 transition">Habilidades</a>
                <a href="#strengths" class="hover:text-sky-400 transition">Fortalezas & Áreas</a>
                <a href="#projects" class="hover:text-sky-400 transition">Proyectos</a>
                <a href="#languages" class="hover:text-sky-400 transition">Idiomas</a>
            </nav>
            <div class="flex items-center space-x-3">
                <a href="https://github.com" target="_blank" class="p-2 rounded-lg bg-slate-900 border border-slate-700 hover:bg-slate-800 transition text-slate-300 hover:text-white">
                    <i class="fa-brands fa-github text-lg"></i>
                </a>
                <a href="mailto:contacto@example.com" class="px-4 py-2 text-sm font-medium rounded-lg bg-sky-600 hover:bg-sky-500 text-white shadow-lg shadow-sky-600/30 transition flex items-center space-x-2">
                    <i class="fa-solid fa-paper-plane text-xs"></i>
                    <span>Contactar</span>
                </a>
            </div>
        </div>
    </header>

    <main class="max-w-6xl mx-auto px-6 py-12 space-y-20">

        <section id="about" class="grid grid-cols-1 lg:grid-cols-12 gap-10 items-center pt-6">
            <div class="lg:col-span-7 space-y-6">
                <div class="inline-flex items-center space-x-2 px-3 py-1.5 rounded-full bg-sky-950/80 border border-sky-800/60 text-sky-400 text-xs font-semibold tracking-wide">
                    <span class="w-2 h-2 rounded-full bg-sky-400 animate-pulse"></span>
                    <span>Disponible para nuevos proyectos y retos</span>
                </div>
                <h1 class="text-4xl sm:text-6xl font-extrabold tracking-tight leading-tight">
                    Hola, soy <span class="gradient-text">Adriel Hernández Hernández</span>
                </h1>
                <p class="text-lg text-slate-300 leading-relaxed">
                    Desarrollador apasionado por la creación de soluciones digitales eficientes, escalables y con un enfoque riguroso. Combino la lógica de la programación con una sólida base en matemáticas y tutoría, buscando siempre optimizar procesos y transmitir conocimiento de valor.
                </p>
                <div class="flex flex-wrap gap-4 pt-2">
                    <a href="#projects" class="px-6 py-3 rounded-xl bg-gradient-to-r from-sky-500 to-indigo-600 text-white font-semibold shadow-lg shadow-indigo-500/25 hover:opacity-95 transition flex items-center space-x-2">
                        <span>Ver Proyectos</span>
                        <i class="fa-solid fa-arrow-down text-xs"></i>
                    </a>
                    <a href="#skills" class="px-6 py-3 rounded-xl bg-slate-900 border border-slate-700 text-slate-300 font-semibold hover:bg-slate-800 hover:text-white transition">
                        Explorar Habilidades
                    </a>
                </div>
                <!-- GitHub Stats Badge Preview simulation -->
                <div class="pt-4 flex flex-wrap items-center gap-4 text-xs text-slate-400">
                    <div class="flex items-center space-x-1.5 bg-slate-900/80 px-3 py-1.5 rounded-lg border border-slate-800">
                        <i class="fa-solid fa-location-dot text-sky-400"></i>
                        <span>México</span>
                    </div>
                    <div class="flex items-center space-x-1.5 bg-slate-900/80 px-3 py-1.5 rounded-lg border border-slate-800">
                        <i class="fa-solid fa-code text-indigo-400"></i>
                        <span>Full-Stack & Lógica</span>
                    </div>
                    <div class="flex items-center space-x-1.5 bg-slate-900/80 px-3 py-1.5 rounded-lg border border-slate-800">
                        <i class="fa-solid fa-graduation-cap text-emerald-400"></i>
                        <span>Matemáticas & Tutoría</span>
                    </div>
                </div>
            </div>

            <!-- Profile Avatar / GitHub style Card -->
            <div class="lg:col-span-5 flex justify-center">
                <div class="relative w-full max-w-sm">
                    <div class="absolute -inset-1 rounded-3xl bg-gradient-to-r from-sky-500 via-indigo-500 to-purple-600 opacity-30 blur-xl"></div>
                    <div class="relative glass-card rounded-3xl p-6 shadow-2xl border border-slate-700/80 space-y-6">
                        <div class="flex items-center space-x-4">
                            <div class="relative">
                                <img src="https://images.unsplash.com/photo-1534528741775-53994a69daeb?auto=format&fit=crop&q=80&w=300" alt="Adriel Hernández Hernández" class="w-20 h-20 rounded-2xl object-cover border-2 border-sky-500 shadow-md" onerror="this.src='https://placehold.co/150x150/0f172a/38bdf8?text=AH'">
                                <div class="absolute -bottom-1 -right-1 bg-emerald-500 w-5 h-5 rounded-full border-4 border-slate-900" title="Activo"></div>
                            </div>
                            <div>
                                <h3 class="font-bold text-lg text-white">Adriel Hernández H.</h3>
                                <p class="text-xs text-sky-400 font-medium">@adriel-hernandez</p>
                                <div class="flex items-center space-x-2 mt-2">
                                    <span class="px-2 py-0.5 rounded text-[10px] font-semibold bg-sky-950 text-sky-300 border border-sky-800">Developer</span>
                                    <span class="px-2 py-0.5 rounded text-[10px] font-semibold bg-indigo-950 text-indigo-300 border border-indigo-800">Tutor</span>
                                </div>
                            </div>
                        </div>
                        <div class="border-t border-slate-800 pt-4 space-y-3">
                            <div class="flex justify-between text-xs text-slate-400">
                                <span>Repositorios principales</span>
                                <span class="font-bold text-white">14+</span>
                            </div>
                            <div class="flex justify-between text-xs text-slate-400">
                                <span>Contribuciones este año</span>
                                <span class="font-bold text-emerald-400">350+</span>
                            </div>
                            <div class="flex justify-between text-xs text-slate-400">
                                <span>Áreas de enfoque</span>
                                <span class="font-bold text-purple-400">Web & STEM</span>
                            </div>
                        </div>
                        <!-- Mini contribution heatmap simulation -->
                        <div class="bg-slate-900/90 rounded-xl p-3 border border-slate-800 space-y-2">
                            <div class="text-[11px] font-medium text-slate-400">Actividad reciente en GitHub</div>
                            <div class="grid grid-cols-12 gap-1">
                                <div class="h-3 rounded-sm bg-emerald-900"></div>
                                <div class="h-3 rounded-sm bg-emerald-700"></div>
                                <div class="h-3 rounded-sm bg-emerald-500"></div>
                                <div class="h-3 rounded-sm bg-slate-800"></div>
                                <div class="h-3 rounded-sm bg-emerald-600"></div>
                                <div class="h-3 rounded-sm bg-emerald-400"></div>
                                <div class="h-3 rounded-sm bg-emerald-500"></div>
                                <div class="h-3 rounded-sm bg-emerald-800"></div>
                                <div class="h-3 rounded-sm bg-emerald-600"></div>
                                <div class="h-3 rounded-sm bg-emerald-400"></div>
                                <div class="h-3 rounded-sm bg-emerald-700"></div>
                                <div class="h-3 rounded-sm bg-emerald-500"></div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <section id="skills" class="space-y-8">
            <div class="text-center max-w-2xl mx-auto space-y-3">
                <h2 class="text-3xl font-bold tracking-tight">Habilidades & Tecnologías</h2>
                <p class="text-slate-400 text-sm">Herramientas y lenguajes que domino para construir software robusto y soluciones analíticas.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                <!-- Programming Category -->
                <div class="glass-card rounded-2xl p-6 border border-slate-800 space-y-4 hover:border-sky-500/50 transition">
                    <div class="flex items-center space-x-3">
                        <div class="w-10 h-10 rounded-xl bg-sky-500/10 text-sky-400 flex items-center justify-center font-bold text-lg">
                            <i class="fa-solid fa-code"></i>
                        </div>
                        <h3 class="font-semibold text-lg">Programación</h3>
                    </div>
                    <p class="text-xs text-slate-400">Desarrollo backend y frontend, estructuración de bases de datos y algoritmos eficientes.</p>
                    <div class="flex flex-wrap gap-2 pt-2">
                        <span class="px-3 py-1 bg-slate-900 border border-slate-700 rounded-lg text-xs font-medium text-sky-300 flex items-center space-x-1.5">
                            <i class="fa-brands fa-js text-yellow-400"></i> <span>JavaScript / TS</span>
                        </span>
                        <span class="px-3 py-1 bg-slate-900 border border-slate-700 rounded-lg text-xs font-medium text-sky-300 flex items-center space-x-1.5">
                            <i class="fa-brands fa-python text-blue-400"></i> <span>Python</span>
                        </span>
                        <span class="px-3 py-1 bg-slate-900 border border-slate-700 rounded-lg text-xs font-medium text-sky-300 flex items-center space-x-1.5">
                            <i class="fa-brands fa-html5 text-orange-500"></i> <span>HTML5 / CSS3</span>
                        </span>
                        <span class="px-3 py-1 bg-slate-900 border border-slate-700 rounded-lg text-xs font-medium text-sky-300 flex items-center space-x-1.5">
                            <i class="fa-brands fa-react text-cyan-400"></i> <span>React.js</span>
                        </span>
                        <span class="px-3 py-1 bg-slate-900 border border-slate-700 rounded-lg text-xs font-medium text-sky-300 flex items-center space-x-1.5">
                            <i class="fa-solid fa-database text-emerald-400"></i> <span>SQL / NoSQL</span>
                        </span>
                    </div>
                </div>

                <!-- Tools Category -->
                <div class="glass-card rounded-2xl p-6 border border-slate-800 space-y-4 hover:border-indigo-500/50 transition">
                    <div class="flex items-center space-x-3">
                        <div class="w-10 h-10 rounded-xl bg-indigo-500/10 text-indigo-400 flex items-center justify-center font-bold text-lg">
                            <i class="fa-solid fa-toolbox"></i>
                        </div>
                        <h3 class="font-semibold text-lg">Herramientas & DevOps</h3>
                    </div>
                    <p class="text-xs text-slate-400">Control de versiones, entornos de desarrollo y flujos de trabajo modernos.</p>
                    <div class="flex flex-wrap gap-2 pt-2">
                        <span class="px-3 py-1 bg-slate-900 border border-slate-700 rounded-lg text-xs font-medium text-indigo-300 flex items-center space-x-1.5">
                            <i class="fa-brands fa-git-alt text-red-500"></i> <span>Git & GitHub</span>
                        </span>
                        <span class="px-3 py-1 bg-slate-900 border border-slate-700 rounded-lg text-xs font-medium text-indigo-300 flex items-center space-x-1.5">
                            <i class="fa-brands fa-docker text-sky-400"></i> <span>Docker Basics</span>
                        </span>
                        <span class="px-3 py-1 bg-slate-900 border border-slate-700 rounded-lg text-xs font-medium text-indigo-300 flex items-center space-x-1.5">
                            <i class="fa-solid fa-terminal text-slate-300"></i> <span>Linux / Bash</span>
                        </span>
                        <span class="px-3 py-1 bg-slate-900 border border-slate-700 rounded-lg text-xs font-medium text-indigo-300 flex items-center space-x-1.5">
                            <i class="fa-solid fa-fire text-amber-500"></i> <span>Tailwind CSS</span>
                        </span>
                        <span class="px-3 py-1 bg-slate-900 border border-slate-700 rounded-lg text-xs font-medium text-indigo-300 flex items-center space-x-1.5">
                            <i class="fa-solid fa-code-branch text-purple-400"></i> <span>VS Code</span>
                        </span>
                    </div>
                </div>

                <!-- Mathematics / Tutoring Category -->
                <div class="glass-card rounded-2xl p-6 border border-slate-800 space-y-4 hover:border-emerald-500/50 transition">
                    <div class="flex items-center space-x-3">
                        <div class="w-10 h-10 rounded-xl bg-emerald-500/10 text-emerald-400 flex items-center justify-center font-bold text-lg">
                            <i class="fa-solid fa-square-root-variable"></i>
                        </div>
                        <h3 class="font-semibold text-lg">Matemáticas & Tutoría</h3>
                    </div>
                    <p class="text-xs text-slate-400">Pensamiento analítico avanzado, resolución de problemas complejos y pedagogía.</p>
                    <div class="flex flex-wrap gap-2 pt-2">
                        <span class="px-3 py-1 bg-slate-900 border border-slate-700 rounded-lg text-xs font-medium text-emerald-300 flex items-center space-x-1.5">
                            <i class="fa-solid fa-calculator text-emerald-400"></i> <span>Cálculo & Álgebra</span>
                        </span>
                        <span class="px-3 py-1 bg-slate-900 border border-slate-700 rounded-lg text-xs font-medium text-emerald-300 flex items-center space-x-1.5">
                            <i class="fa-solid fa-brain text-emerald-400"></i> <span>Pensamiento Lógico</span>
                        </span>
                        <span class="px-3 py-1 bg-slate-900 border border-slate-700 rounded-lg text-xs font-medium text-emerald-300 flex items-center space-x-1.5">
                            <i class="fa-solid fa-chalkboard-user text-emerald-400"></i> <span>Docencia / Mentoría</span>
                        </span>
                        <span class="px-3 py-1 bg-slate-900 border border-slate-700 rounded-lg text-xs font-medium text-emerald-300 flex items-center space-x-1.5">
                            <i class="fa-solid fa-chart-line text-emerald-400"></i> <span>Estadística Aplicada</span>
                        </span>
                    </div>
                </div>
            </div>
        </section>

        <section id="strengths" class="grid grid-cols-1 md:grid-cols-2 gap-8">
            <!-- Professional Strengths -->
            <div class="glass-card rounded-2xl p-8 border border-emerald-500/20 space-y-6 relative overflow-hidden">
                <div class="absolute top-0 right-0 w-32 h-32 bg-emerald-500/5 rounded-full blur-2xl"></div>
                <div class="flex items-center space-x-3">
                    <div class="w-10 h-10 rounded-xl bg-emerald-500/20 text-emerald-400 flex items-center justify-center font-bold">
                        <i class="fa-solid fa-shield-halved"></i>
                    </div>
                    <div>
                        <h3 class="text-xl font-bold">Habilidades Profesionales</h3>
                        <p class="text-xs text-slate-400">Fortalezas clave que potencian mi rendimiento</p>
                    </div>
                </div>
                <ul class="space-y-4">
                    <li class="flex items-start space-x-3">
                        <i class="fa-solid fa-circle-check text-emerald-400 mt-1"></i>
                        <div>
                            <strong class="text-slate-200 block text-sm">Resolución Analítica de Problemas</strong>
                            <p class="text-xs text-slate-400">Capacidad para descomponer retos complejos de programación o matemáticas en pasos sencillos y manejables.</p>
                        </div>
                    </li>
                    <li class="flex items-start space-x-3">
                        <i class="fa-solid fa-circle-check text-emerald-400 mt-1"></i>
                        <div>
                            <strong class="text-slate-200 block text-sm">Comunicación Efectiva & Empatía Didáctica</strong>
                            <p class="text-xs text-slate-400">Habilidad probada como tutor para explicar conceptos abstractos a personas con diversos niveles de comprensión.</p>
                        </div>
                    </li>
                    <li class="flex items-start space-x-3">
                        <i class="fa-solid fa-circle-check text-emerald-400 mt-1"></i>
                        <div>
                            <strong class="text-slate-200 block text-sm">Aprendizaje Autónomo y Constante</strong>
                            <p class="text-xs text-slate-400">Adaptabilidad rápida ante nuevas tecnologías, marcos de trabajo o metodologías de desarrollo.</p>
                        </div>
                    </li>
                </ul>
            </div>

            <!-- Growth Areas (Debilidades framed professionally) -->
            <div class="glass-card rounded-2xl p-8 border border-sky-500/20 space-y-6 relative overflow-hidden">
                <div class="absolute top-0 right-0 w-32 h-32 bg-sky-500/5 rounded-full blur-2xl"></div>
                <div class="flex items-center space-x-3">
                    <div class="w-10 h-10 rounded-xl bg-sky-500/20 text-sky-400 flex items-center justify-center font-bold">
                        <i class="fa-solid fa-seedling"></i>
                    </div>
                    <div>
                        <h3 class="text-xl font-bold">Áreas de Oportunidad</h3>
                        <p class="text-xs text-slate-400">Retos actuales en desarrollo y plan de mejora continua</p>
                    </div>
                </div>
                <ul class="space-y-4">
                    <li class="flex items-start space-x-3">
                        <i class="fa-solid fa-arrow-trend-up text-sky-400 mt-1"></i>
                        <div>
                            <strong class="text-slate-200 block text-sm">Gestión del Tiempo en Múltiples Proyectos</strong>
                            <p class="text-xs text-slate-400">Al involucrarme en desarrollo y tutorías simultáneas, perfecciono continuamente técnicas avanzadas de priorización y metodologías ágiles.</p>
                        </div>
                    </li>
                    <li class="flex items-start space-x-3">
                        <i class="fa-solid fa-arrow-trend-up text-sky-400 mt-1"></i>
                        <div>
                            <strong class="text-slate-200 block text-sm">Delegación de Tareas Técnicas</strong>
                            <p class="text-xs text-slate-400">Tiendo a asumir la responsabilidad completa de las soluciones; estoy trabajando activamente en delegar y liderar equipos de trabajo en proyectos compartidos.</p>
                        </div>
                    </li>
                    <li class="flex items-start space-x-3">
                        <i class="fa-solid fa-arrow-trend-up text-sky-400 mt-1"></i>
                        <div>
                            <strong class="text-slate-200 block text-sm">Profundización en Arquitecturas Cloud Avanzadas</strong>
                            <p class="text-xs text-slate-400">Expandiendo mi experiencia más allá del desarrollo local hacia despliegues complejos en la nube (AWS / Serverless).</p>
                        </div>
                    </li>
                </ul>
            </div>
        </section>

        <section id="projects" class="space-y-8">
            <div class="flex flex-col md:flex-row md:items-end justify-between gap-4">
                <div>
                    <h2 class="text-3xl font-bold tracking-tight">Proyectos Destacados</h2>
                    <p class="text-slate-400 text-sm mt-1">Algunos de los trabajos más representativos en mi repositorio de GitHub.</p>
                </div>
                <a href="https://github.com" target="_blank" class="text-sm font-semibold text-sky-400 hover:text-sky-300 flex items-center space-x-2">
                    <span>Ver todos en GitHub</span>
                    <i class="fa-solid fa-arrow-up-right-from-square text-xs"></i>
                </a>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                <!-- Project 1 -->
                <div class="glass-card rounded-2xl overflow-hidden border border-slate-800 flex flex-col justify-between hover:border-sky-500/50 transition group">
                    <div class="p-6 space-y-4">
                        <div class="flex justify-between items-start">
                            <div class="w-10 h-10 rounded-xl bg-sky-500/10 text-sky-400 flex items-center justify-center font-bold">
                                <i class="fa-solid fa-calculator"></i>
                            </div>
                            <div class="flex space-x-2 text-slate-400">
                                <a href="#" class="hover:text-white transition"><i class="fa-brands fa-github"></i></a>
                                <a href="#" class="hover:text-white transition"><i class="fa-solid fa-globe"></i></a>
                            </div>
                        </div>
                        <h3 class="font-bold text-lg text-white group-hover:text-sky-400 transition">MathSolver & Tutor App</h3>
                        <p class="text-xs text-slate-400 leading-relaxed">
                            Plataforma interactiva de apoyo matemático diseñada para estudiantes, que genera ejercicios paso a paso y evalúa resultados mediante lógica algorítmica.
                        </p>
                        <div class="flex flex-wrap gap-1.5 pt-2">
                            <span class="px-2.5 py-0.5 bg-slate-900 border border-slate-700 rounded text-[11px] text-sky-300">JavaScript</span>
                            <span class="px-2.5 py-0.5 bg-slate-900 border border-slate-700 rounded text-[11px] text-sky-300">Tailwind</span>
                            <span class="px-2.5 py-0.5 bg-slate-900 border border-slate-700 rounded text-[11px] text-sky-300">Node.js</span>
                        </div>
                    </div>
                    <div class="px-6 py-4 bg-slate-900/60 border-t border-slate-800/80 flex justify-between items-center text-xs text-slate-400">
                        <span>Actualizado recientemente</span>
                        <span class="flex items-center space-x-1 text-emerald-400"><i class="fa-solid fa-star text-[10px]"></i> <span>24</span></span>
                    </div>
                </div>

                <!-- Project 2 -->
                <div class="glass-card rounded-2xl overflow-hidden border border-slate-800 flex flex-col justify-between hover:border-indigo-500/50 transition group">
                    <div class="p-6 space-y-4">
                        <div class="flex justify-between items-start">
                            <div class="w-10 h-10 rounded-xl bg-indigo-500/10 text-indigo-400 flex items-center justify-center font-bold">
                                <i class="fa-solid fa-database"></i>
                            </div>
                            <div class="flex space-x-2 text-slate-400">
                                <a href="#" class="hover:text-white transition"><i class="fa-brands fa-github"></i></a>
                                <a href="#" class="hover:text-white transition"><i class="fa-solid fa-globe"></i></a>
                            </div>
                        </div>
                        <h3 class="font-bold text-lg text-white group-hover:text-indigo-400 transition">TaskFlow API</h3>
                        <p class="text-xs text-slate-400 leading-relaxed">
                            API RESTful construida para la gestión optimizada de tareas y proyectos académicos, con autenticación segura JWT y documentación interactiva.
                        </p>
                        <div class="flex flex-wrap gap-1.5 pt-2">
                            <span class="px-2.5 py-0.5 bg-slate-900 border border-slate-700 rounded text-[11px] text-indigo-300">Python</span>
                            <span class="px-2.5 py-0.5 bg-slate-900 border border-slate-700 rounded text-[11px] text-indigo-300">Flask</span>
                            <span class="px-2.5 py-0.5 bg-slate-900 border border-slate-700 rounded text-[11px] text-indigo-300">PostgreSQL</span>
                        </div>
                    </div>
                    <div class="px-6 py-4 bg-slate-900/60 border-t border-slate-800/80 flex justify-between items-center text-xs text-slate-400">
                        <span>Backend robusto</span>
                        <span class="flex items-center space-x-1 text-emerald-400"><i class="fa-solid fa-star text-[10px]"></i> <span>19</span></span>
                    </div>
                </div>

                <!-- Project 3 -->
                <div class="glass-card rounded-2xl overflow-hidden border border-slate-800 flex flex-col justify-between hover:border-purple-500/50 transition group">
                    <div class="p-6 space-y-4">
                        <div class="flex justify-between items-start">
                            <div class="w-10 h-10 rounded-xl bg-purple-500/10 text-purple-400 flex items-center justify-center font-bold">
                                <i class="fa-solid fa-chart-pie"></i>
                            </div>
                            <div class="flex space-x-2 text-slate-400">
                                <a href="#" class="hover:text-white transition"><i class="fa-brands fa-github"></i></a>
                                <a href="#" class="hover:text-white transition"><i class="fa-solid fa-globe"></i></a>
                            </div>
                        </div>
                        <h3 class="font-bold text-lg text-white group-hover:text-purple-400 transition">Portfolio Dashboard</h3>
                        <p class="text-xs text-slate-400 leading-relaxed">
                            Panel de control personal con estadísticas en tiempo real y componentes modulares responsivos para visualización de métricas de rendimiento.
                        </p>
                        <div class="flex flex-wrap gap-1.5 pt-2">
                            <span class="px-2.5 py-0.5 bg-slate-900 border border-slate-700 rounded text-[11px] text-purple-300">React</span>
                            <span class="px-2.5 py-0.5 bg-slate-900 border border-slate-700 rounded text-[11px] text-purple-300">Tailwind</span>
                            <span class="px-2.5 py-0.5 bg-slate-900 border border-slate-700 rounded text-[11px] text-purple-300">Vite</span>
                        </div>
                    </div>
                    <div class="px-6 py-4 bg-slate-900/60 border-t border-slate-800/80 flex justify-between items-center text-xs text-slate-400">
                        <span>Modern UI/UX</span>
                        <span class="flex items-center space-x-1 text-emerald-400"><i class="fa-solid fa-star text-[10px]"></i> <span>31</span></span>
                    </div>
                </div>
            </div>
        </section>

        <section id="languages" class="space-y-8">
            <div class="text-center max-w-2xl mx-auto space-y-3">
                <h2 class="text-3xl font-bold tracking-tight">Idiomas</h2>
                <p class="text-slate-400 text-sm">Competencia lingüística para entornos profesionales y multiculturales.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-6 max-w-3xl mx-auto">
                <!-- Spanish -->
                <div class="glass-card rounded-2xl p-6 border border-slate-800 space-y-4">
                    <div class="flex justify-between items-center">
                        <div class="flex items-center space-x-3">
                            <span class="text-2xl">🇲🇽</span>
                            <div>
                                <h4 class="font-bold text-white">Español</h4>
                                <span class="text-xs text-slate-400">Lengua Nativa</span>
                            </div>
                        </div>
                        <span class="px-3 py-1 rounded-full bg-emerald-500/10 text-emerald-400 text-xs font-semibold border border-emerald-500/20">C2 - Avanzado</span>
                    </div>
                    <div class="w-full bg-slate-900 rounded-full h-2 overflow-hidden border border-slate-800">
                        <div class="bg-gradient-to-r from-emerald-500 to-teal-400 h-full rounded-full" style="width: 100%"></div>
                    </div>
                </div>

                <!-- English -->
                <div class="glass-card rounded-2xl p-6 border border-slate-800 space-y-4">
                    <div class="flex justify-between items-center">
                        <div class="flex items-center space-x-3">
                            <span class="text-2xl">🇺🇸</span>
                            <div>
                                <h4 class="font-bold text-white">Inglés</h4>
                                <span class="text-xs text-slate-400">Profesional / Técnico</span>
                            </div>
                        </div>
                        <span class="px-3 py-1 rounded-full bg-sky-500/10 text-sky-400 text-xs font-semibold border border-sky-500/20">B2 / C1 - Profesional</span>
                    </div>
                    <div class="w-full bg-slate-900 rounded-full h-2 overflow-hidden border border-slate-800">
                        <div class="bg-gradient-to-r from-sky-500 to-indigo-500 h-full rounded-full" style="width: 85%"></div>
                    </div>
                </div>
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer class="glass-card border-t border-slate-800/80 mt-20 py-10 px-6">
        <div class="max-w-6xl mx-auto flex flex-col md:flex-row justify-between items-center gap-6">
            <div class="flex items-center space-x-3">
                <div class="w-8 h-8 rounded-lg bg-gradient-to-tr from-sky-500 to-indigo-600 flex items-center justify-center font-bold text-sm text-white">
                    AH
                </div>
                <span class="text-sm font-semibold text-slate-300">Adriel Hernández Hernández &copy; 2026</span>
            </div>
            <div class="flex items-center space-x-6 text-slate-400 text-sm">
                <a href="https://github.com" target="_blank" class="hover:text-sky-400 transition"><i class="fa-brands fa-github text-lg"></i></a>
                <a href="https://linkedin.com" target="_blank" class="hover:text-sky-400 transition"><i class="fa-brands fa-linkedin text-lg"></i></a>
                <a href="mailto:contacto@example.com" class="hover:text-sky-400 transition"><i class="fa-solid fa-envelope text-lg"></i></a>
            </div>
        </div>
    </footer>

</body>
</html>
