<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Biografía de Desarrollador</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://unpkg.com/feather-icons"></script>
    <style>
        .code-theme {
            background-color: #1e1e1e;
            color: #d4d4d4;
            font-family: 'Fira Code', monospace;
        }
        .typewriter {
            overflow: hidden;
            border-right: .15em solid #569cd6;
            white-space: nowrap;
            margin: 0 auto;
            letter-spacing: .15em;
            animation: typing 3.5s steps(40, end), blink-caret .75s step-end infinite;
        }
        @keyframes typing {
            from { width: 0 }
            to { width: 100% }
        }
        @keyframes blink-caret {
            from, to { border-color: transparent }
            50% { border-color: #569cd6 }
        }
        .skill-bar {
            background-color: #333;
            border-radius: 3px;
        }
        .skill-fill {
            background-color: #4EC9B0;
            height: 10px;
            border-radius: 3px;
            transition: width 1s ease-in-out;
        }
    </style>
</head>
<body class="code-theme min-h-screen p-8">
    <div class="max-w-4xl mx-auto">
        <header class="text-center mb-12">
            <div class="flex justify-center mb-6">
                <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/81edc47b-db34-4aaa-9db3-28c1edbfb488.png" alt="Dev avatar - portrait of a professional developer with glasses in dark mode UI colors" class="rounded-full border-4 border-[#569cd6]" />
            </div>
            <h1 class="typewriter text-4xl font-bold mb-2 text-[#569cd6]"># Gianinna Campos</h1>
            <h2 class="text-xl text-[#9cdcfe] mb-4">Desarrollador Full Stack</h2>
            <div class="flex justify-center space-x-4">
                <a href="#" class="text-[#d7ba7d] hover:text-[#ffd700]">
                    <i data-feather="github"></i>
                </a>
                <a href="#" class="text-[#d7ba7d] hover:text-[#ffd700]">
                    <i data-feather="linkedin"></i>
                </a>
                <a href="#" class="text-[#d7ba7d] hover:text-[#ffd700]">
                    <i data-feather="twitter"></i>
                </a>
            </div>
        </header>

        <section class="mb-12">
            <h3 class="text-2xl font-bold mb-4 text-[#569cd6] border-b border-[#333] pb-2">// Sobre Mí</h3>
            <div class="grid grid-cols-1 md:grid-cols-4 gap-6">
                <div class="md:col-span-3">
                    <p class="mb-4 text-[#d4d4d4]">Apasionado desarrollador de software con 5+ años de experiencia construyendo aplicaciones web y móviles. Me especializo en JavaScript/TypeScript, React, Node.js y arquitecturas cloud.</p>
                    <p class="text-[#d4d4d4]">Mi enfoque combina código limpio, buenas prácticas y diseño UX. Siempre aprendiendo nuevas tecnologías y mejorando mis habilidades.</p>
                </div>
                <div class="bg-[#333] p-4 rounded">
                    <h4 class="text-[#9cdcfe] mb-2">Detalles</h4>
                    <ul class="text-sm space-y-2">
                        <li class="flex items-center">
                            <i data-feather="map-pin" class="w-4 h-4 mr-2 text-[#d7ba7d]"></i>
                            <span>Barcelona, España</span>
                        </li>
                        <li class="flex items-center">
                            <i data-feather="mail" class="w-4 h-4 mr-2 text-[#d7ba7d]"></i>
                            <span>email@ejemplo.com</span>
                        </li>
                        <li class="flex items-center">
                            <i data-feather="briefcase" class="w-4 h-4 mr-2 text-[#d7ba7d]"></i>
                            <span>Disponible para proyectos</span>
                        </li>
                    </ul>
                </div>
            </div>
        </section>

        <section class="mb-12">
            <h3 class="text-2xl font-bold mb-4 text-[#569cd6] border-b border-[#333] pb-2">// Habilidades Técnicas</h3>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                <div>
                    <h4 class="text-xl text-[#9cdcfe] mb-3">Frontend</h4>
                    <div class="space-y-4">
                        <div>
                            <div class="flex justify-between mb-1">
                                <span>JavaScript/TypeScript</span>
                                <span>90%</span>
                            </div>
                            <div class="skill-bar w-full">
                                <div class="skill-fill" style="width: 90%;"></div>
                            </div>
                        </div>
                        <div>
                            <div class="flex justify-between mb-1">
                                <span>React</span>
                                <span>85%</span>
                            </div>
                            <div class="skill-bar w-full">
                                <div class="skill-fill" style="width: 85%;"></div>
                            </div>
                        </div>
                    </div>
                </div>
                <div>
                    <h4 class="text-xl text-[#9cdcfe] mb-3">Backend</h4>
                    <div class="space-y-4">
                        <div>
                            <div class="flex justify-between mb-1">
                                <span>Node.js</span>
                                <span>85%</span>
                            </div>
                            <div class="skill-bar w-full">
                                <div class="skill-fill" style="width: 85%;"></div>
                            </div>
                        </div>
                        <div>
                            <div class="flex justify-between mb-1">
                                <span>Python</span>
                                <span>75%</span>
                            </div>
                            <div class="skill-bar w-full">
                                <div class="skill-fill" style="width: 75%;"></div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <section class="mb-12">
            <h3 class="text-2xl font-bold mb-4 text-[#569cd6] border-b border-[#333] pb-2">// Experiencia</h3>
            <div class="space-y-6">
                <div class="bg-[#252526] p-4 rounded border-l-4 border-[#569cd6]">
                    <div class="flex justify-between items-start">
                        <div>
                            <h4 class="text-xl text-[#9cdcfe]">Ingeniero de Software Senior</h4>
                            <p class="text-[#d7ba7d]">Empresa Tech</p>
                        </div>
                        <div class="text-sm text-[#d4d4d4]">2020 - Presente</div>
                    </div>
                    <ul class="mt-3 space-y-2 text-sm list-disc list-inside">
                        <li>Lideré el desarrollo de la plataforma principal</li>
                        <li>Implementé arquitectura de microservicios</li>
                        <li>Mentoría a desarrolladores junior</li>
                    </ul>
                </div>
            </div>
        </section>

        <section class="mb-12">
            <h3 class="text-2xl font-bold mb-4 text-[#569cd6] border-b border-[#333] pb-2">// Proyectos Destacados</h3>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                <div class="bg-[#333] p-4 rounded hover:bg-[#252526] transition">
                    <h4 class="text-xl text-[#9cdcfe] mb-2">Plataforma E-commerce</h4>
                    <p class="text-sm mb-3">Solución completa con carrito, pagos y panel de administración</p>
                    <div class="flex flex-wrap gap-2">
                        <span class="px-2 py-1 bg-[#252526] text-xs rounded">React</span>
                        <span class="px-2 py-1 bg-[#252526] text-xs rounded">Node.js</span>
                        <span class="px-2 py-1 bg-[#252526] text-xs rounded">MongoDB</span>
                    </div>
                </div>
                <div class="bg-[#333] p-4 rounded hover:bg-[#252526] transition">
                    <h4 class="text-xl text-[#9cdcfe] mb-2">Aplicación móvil</h4>
                    <p class="text-sm mb-3">App de productividad con sincronización en tiempo real</p>
                    <div class="flex flex-wrap gap-2">
                        <span class="px-2 py-1 bg-[#252526] text-xs rounded">React Native</span>
                        <span class="px-2 py-1 bg-[#252526] text-xs rounded">Firebase</span>
                        <span class="px-2 py-1 bg-[#252526] text-xs rounded">Redux</span>
                    </div>
                </div>
            </div>
        </section>

        <footer class="text-center text-sm text-[#757575] mt-12">
            <p>© 2023 - Todos los derechos reservados</p>
        </footer>
    </div>

    <script>
        feather.replace();
        
        // Animar barras de habilidades
        document.addEventListener('DOMContentLoaded', function() {
            const skillBars = document.querySelectorAll('.skill-fill');
            skillBars.forEach(bar => {
                const width = bar.style.width;
                bar.style.width = '0';
                setTimeout(() => {
                    bar.style.width = width;
                }, 500);
            });
        });
    </script>
</body>
</html>

