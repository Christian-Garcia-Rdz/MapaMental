<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mapa Mental: Estándares y Métricas en Ingeniería de Software</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #e0e7ff 0%, #f0f4ff 100%);
            min-height: 100vh;
            padding: 40px 20px;
            overflow-x: hidden;
        }

        .header {
            text-align: center;
            margin-bottom: 60px;
        }

        .header h1 {
            color: #94a3b8;
            font-size: 3em;
            font-weight: 300;
            letter-spacing: 4px;
        }

        .container {
            max-width: 1400px;
            margin: 0 auto;
            position: relative;
            height: 1200px;
        }

        .central-circle {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            width: 320px;
            height: 320px;
            background: #475569;
            border-radius: 50%;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            box-shadow: 0 20px 60px rgba(71, 85, 105, 0.3);
            z-index: 10;
        }

        .central-circle h2 {
            color: white;
            font-size: 1.4em;
            text-align: center;
            padding: 0 30px;
            line-height: 1.6;
            font-weight: 600;
        }

        .icon-center {
            font-size: 3em;
            margin-bottom: 15px;
        }

        svg {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: 1;
            pointer-events: none;
        }

        .branch {
            position: absolute;
            width: 280px;
            cursor: pointer;
            transition: all 0.3s ease;
        }

        .branch:hover {
            transform: scale(1.05);
            z-index: 100;
        }

        .node-circle {
            width: 80px;
            height: 80px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 2em;
            box-shadow: 0 8px 20px rgba(0,0,0,0.15);
            margin: 0 auto 15px;
        }

        .color-1 { background: #f472b6; }
        .color-2 { background: #60a5fa; }
        .color-3 { background: #34d399; }
        .color-4 { background: #fbbf24; }
        .color-5 { background: #a78bfa; }
        .color-6 { background: #fb923c; }
        .color-7 { background: #ec4899; }
        .color-8 { background: #8b5cf6; }

        .info-box {
            background: white;
            padding: 20px;
            border-radius: 15px;
            box-shadow: 0 8px 25px rgba(0,0,0,0.1);
            min-height: 180px;
        }

        .info-box h3 {
            color: #334155;
            font-size: 1.2em;
            margin-bottom: 12px;
            font-weight: 600;
        }

        .info-box p {
            color: #64748b;
            font-size: 0.9em;
            line-height: 1.6;
            margin-bottom: 10px;
        }

        .info-box ul {
            color: #64748b;
            font-size: 0.85em;
            line-height: 1.7;
            margin-left: 20px;
            display: none;
        }

        .info-box ul li {
            margin: 6px 0;
        }

        .branch.expanded .info-box ul {
            display: block;
            animation: fadeIn 0.3s ease;
        }

        .branch.expanded .info-box {
            min-height: auto;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(-10px); }
            to { opacity: 1; transform: translateY(0); }
        }

        /* Posicionamiento de los nodos */
        .branch-1 { top: 5%; left: 15%; }
        .branch-2 { top: 5%; right: 15%; }
        .branch-3 { top: 28%; left: 2%; }
        .branch-4 { top: 28%; right: 2%; }
        .branch-5 { bottom: 28%; left: 2%; }
        .branch-6 { bottom: 28%; right: 2%; }
        .branch-7 { bottom: 5%; left: 15%; }
        .branch-8 { bottom: 5%; right: 15%; }

        .toggle-hint {
            text-align: center;
            color: #94a3b8;
            font-size: 0.8em;
            margin-top: 10px;
            font-style: italic;
        }

        @media (max-width: 1200px) {
            .container {
                height: auto;
                position: static;
            }

            .branch {
                position: static;
                margin: 30px auto;
                max-width: 400px;
            }

            .central-circle {
                position: static;
                transform: none;
                margin: 40px auto;
            }

            svg {
                display: none;
            }
        }

        .legend {
            max-width: 1400px;
            margin: 80px auto 40px;
            padding: 30px;
            background: white;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
        }

        .legend h3 {
            color: #334155;
            margin-bottom: 15px;
            font-size: 1.3em;
        }

        .legend p {
            color: #64748b;
            line-height: 1.8;
            margin-bottom: 10px;
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>Mapa Mental</h1>
    </div>

    <div class="container">
        <svg id="connections"></svg>

        <div class="central-circle">
            <div class="icon-center">💻</div>
            <h2>ESTÁNDARES Y MÉTRICAS<br>Ingeniería de Software Web</h2>
        </div>

        <!-- Rama 1: CMMI -->
        <div class="branch branch-1" onclick="toggleBranch(this)">
            <div class="node-circle color-1">🏆</div>
            <div class="info-box">
                <h3>CMMI</h3>
                <p>Capability Maturity Model Integration - Modelo de madurez para mejora de procesos</p>
                <ul>
                    <li><strong>5 Niveles:</strong> Inicial, Gestionado, Definido, Cuantitativamente Gestionado, Optimizado</li>
                    <li><strong>22 Áreas de proceso</strong> organizadas por categorías</li>
                    <li>Enfoque en <strong>mejora continua</strong> organizacional</li>
                    <li>Aplicable a desarrollo, servicios y adquisiciones</li>
                    <li>Certificación por niveles de madurez</li>
                </ul>
                <div class="toggle-hint">Click para más detalles</div>
            </div>
        </div>

        <!-- Rama 2: MoProSoft -->
        <div class="branch branch-2" onclick="toggleBranch(this)">
            <div class="node-circle color-2">🇲🇽</div>
            <div class="info-box">
                <h3>MoProSoft</h3>
                <p>Modelo de Procesos para la Industria de Software (NMX-I-059) - Norma mexicana para PyMEs</p>
                <ul>
                    <li><strong>3 Categorías:</strong> Alta Dirección, Gerencia, Operación</li>
                    <li>9 procesos organizados por categoría</li>
                    <li>Adaptado a <strong>pequeñas y medianas empresas</strong></li>
                    <li>Certificación por NYCE</li>
                    <li>Compatible con ISO 9001 y CMMI</li>
                    <li>Enfoque práctico y accesible</li>
                </ul>
                <div class="toggle-hint">Click para más detalles</div>
            </div>
        </div>

        <!-- Rama 3: ISO 27001 -->
        <div class="branch branch-3" onclick="toggleBranch(this)">
            <div class="node-circle color-3">🔒</div>
            <div class="info-box">
                <h3>ISO/IEC 27001</h3>
                <p>Gestión de Seguridad de la Información (SGSI)</p>
                <ul>
                    <li><strong>93 controles</strong> de seguridad en ISO 27002</li>
                    <li>Protección de <strong>confidencialidad, integridad y disponibilidad</strong></li>
                    <li>Gestión de riesgos de seguridad</li>
                    <li>Cumplimiento GDPR y privacidad de datos</li>
                    <li>Cifrado, autenticación y control de accesos</li>
                    <li>Auditorías y certificación internacional</li>
                </ul>
                <div class="toggle-hint">Click para más detalles</div>
            </div>
        </div>

        <!-- Rama 4: ISO 25010 -->
        <div class="branch branch-4" onclick="toggleBranch(this)">
            <div class="node-circle color-4">⭐</div>
            <div class="info-box">
                <h3>ISO/IEC 25010</h3>
                <p>Calidad del Producto Software (SQuaRE)</p>
                <ul>
                    <li><strong>8 características:</strong> Funcionalidad, Eficiencia, Compatibilidad, Usabilidad</li>
                    <li>Fiabilidad, Seguridad, Mantenibilidad, Portabilidad</li>
                    <li>Modelo de evaluación de calidad</li>
                    <li>Métricas objetivas y medibles</li>
                    <li>Aplicable a cualquier tipo de software</li>
                    <li>Base para auditorías de calidad</li>
                </ul>
                <div class="toggle-hint">Click para más detalles</div>
            </div>
        </div>

        <!-- Rama 5: Metodologías Ágiles -->
        <div class="branch branch-5" onclick="toggleBranch(this)">
            <div class="node-circle color-5">⚡</div>
            <div class="info-box">
                <h3>Metodologías Ágiles</h3>
                <p>Scrum, XP, Kanban - Desarrollo iterativo e incremental</p>
                <ul>
                    <li><strong>Scrum:</strong> Sprints, Daily Standups, Retrospectives</li>
                    <li><strong>XP:</strong> Pair Programming, TDD, CI/CD</li>
                    <li><strong>Kanban:</strong> Visualización, WIP limits, flujo continuo</li>
                    <li>Entregas frecuentes y valor temprano</li>
                    <li>Adaptación al cambio</li>
                    <li>Colaboración cliente-equipo</li>
                </ul>
                <div class="toggle-hint">Click para más detalles</div>
            </div>
        </div>

        <!-- Rama 6: Métricas Web -->
        <div class="branch branch-6" onclick="toggleBranch(this)">
            <div class="node-circle color-6">📊</div>
            <div class="info-box">
                <h3>Métricas Web</h3>
                <p>Core Web Vitals y métricas de rendimiento</p>
                <ul>
                    <li><strong>LCP:</strong> Largest Contentful Paint (&lt; 2.5s)</li>
                    <li><strong>FID:</strong> First Input Delay (&lt; 100ms)</li>
                    <li><strong>CLS:</strong> Cumulative Layout Shift (&lt; 0.1)</li>
                    <li><strong>Lighthouse Score:</strong> Auditoría automatizada</li>
                    <li>Time to Interactive, Page Load Time</li>
                    <li>Métricas de Google para ranking SEO</li>
                </ul>
                <div class="toggle-hint">Click para más detalles</div>
            </div>
        </div>

        <!-- Rama 7: OWASP -->
        <div class="branch branch-7" onclick="toggleBranch(this)">
            <div class="node-circle color-7">🛡️</div>
            <div class="info-box">
                <h3>OWASP Top 10</h3>
                <p>Riesgos críticos de seguridad en aplicaciones web</p>
                <ul>
                    <li><strong>A01:</strong> Control de Acceso Roto</li>
                    <li><strong>A02:</strong> Fallas Criptográficas</li>
                    <li><strong>A03:</strong> Inyección SQL, XSS, Command</li>
                    <li><strong>A04:</strong> Diseño Inseguro</li>
                    <li>Configuración incorrecta, componentes vulnerables</li>
                    <li>Guía esencial para desarrollo web seguro</li>
                </ul>
                <div class="toggle-hint">Click para más detalles</div>
            </div>
        </div>

        <!-- Rama 8: Estándares W3C -->
        <div class="branch branch-8" onclick="toggleBranch(this)">
            <div class="node-circle color-8">🌐</div>
            <div class="info-box">
                <h3>Estándares W3C</h3>
                <p>HTML5, CSS3, WCAG - Tecnologías web estándar</p>
                <ul>
                    <li><strong>HTML5:</strong> Estructura semántica moderna</li>
                    <li><strong>CSS3:</strong> Diseño responsive y animaciones</li>
                    <li><strong>WCAG 2.1/2.2:</strong> Accesibilidad (A, AA, AAA)</li>
                    <li><strong>WAI-ARIA:</strong> Accesibilidad para apps ricas</li>
                    <li>REST, OpenAPI, GraphQL para APIs</li>
                    <li>Progressive Web Apps (PWA)</li>
                </ul>
                <div class="toggle-hint">Click para más detalles</div>
            </div>
        </div>
    </div>



    <script>
        function toggleBranch(element) {
            element.classList.toggle('expanded');
        }

        // Dibujar líneas conectoras
        function drawConnections() {
            const svg = document.getElementById('connections');
            const central = document.querySelector('.central-circle');
            const branches = document.querySelectorAll('.branch');
            
            if (window.innerWidth <= 1200) return; // No dibujar en móvil
            
            svg.innerHTML = '';
            
            const centralRect = central.getBoundingClientRect();
            const containerRect = svg.getBoundingClientRect();
            
            const centerX = centralRect.left + centralRect.width / 2 - containerRect.left;
            const centerY = centralRect.top + centralRect.height / 2 - containerRect.top;
            
            branches.forEach(branch => {
                const circle = branch.querySelector('.node-circle');
                const circleRect = circle.getBoundingClientRect();
                
                const branchX = circleRect.left + circleRect.width / 2 - containerRect.left;
                const branchY = circleRect.top + circleRect.height / 2 - containerRect.top;
                
                const line = document.createElementNS('http://www.w3.org/2000/svg', 'line');
                line.setAttribute('x1', centerX);
                line.setAttribute('y1', centerY);
                line.setAttribute('x2', branchX);
                line.setAttribute('y2', branchY);
                line.setAttribute('stroke', '#cbd5e1');
                line.setAttribute('stroke-width', '2');
                line.setAttribute('stroke-dasharray', '5,5');
                
                svg.appendChild(line);
            });
        }

        window.addEventListener('load', drawConnections);
        window.addEventListener('resize', drawConnections);
    </script>
</body>
</html>
