<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Genera Ingresos en Internet | Tu Camino al Éxito</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        /* Estilos Generales y Variables */
        :root {
            --primary: #0d5c46; 
            --secondary: #1a8b6c; 
            --accent: #ffd700; 
            --bg-color: #f0f4f8;
            --text-main: #333;
            --text-light: #555;
            --white: #ffffff;
            --shadow: 0 8px 20px rgba(0, 0, 0, 0.08);
            --transition: all 0.3s ease;
        }

        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background-color: var(--bg-color);
            color: var(--text-main);
            line-height: 1.6;
            overflow-x: hidden;
        }

        /* Header con Efectos */
        header {
            background: linear-gradient(135deg, var(--primary) 0%, var(--secondary) 100%);
            color: var(--white);
            text-align: center;
            padding: 5rem 2rem;
            position: relative;
            box-shadow: 0 4px 15px rgba(0,0,0,0.2);
        }

        h1 {
            font-size: 3.5rem;
            margin: 0;
            font-weight: 700;
            transition: var(--transition);
            display: inline-block;
            cursor: pointer;
        }

        h1:hover {
            transform: scale(1.08) translateY(-5px);
            color: var(--accent);
            text-shadow: 0 10px 25px rgba(255, 215, 0, 0.4);
        }

        header p {
            font-size: 1.2rem;
            margin-top: 1rem;
            opacity: 0.9;
        }

        /* Contenedor Principal */
        .container {
            max-width: 1100px;
            margin: -3rem auto 2rem;
            padding: 0 2rem;
            position: relative;
            z-index: 10;
        }

        section {
            background: var(--white);
            margin-bottom: 3rem;
            padding: 3rem;
            border-radius: 15px;
            box-shadow: var(--shadow);
            transition: var(--transition);
        }

        section:hover {
            box-shadow: 0 12px 30px rgba(0, 0, 0, 0.12);
        }

        h2 {
            color: var(--primary);
            font-size: 2rem;
            margin-top: 0;
            border-bottom: 3px solid var(--secondary);
            display: inline-block;
            padding-bottom: 0.5rem;
            margin-bottom: 1.5rem;
        }

        /* Imágenes de Dinero */
        .image-container {
            text-align: center;
            margin: 2rem 0;
        }

        .image-container img {
            max-width: 100%;
            height: auto;
            border-radius: 12px;
            box-shadow: var(--shadow);
            transition: var(--transition);
            border: 5px solid var(--white);
        }

        .image-container img:hover {
            transform: scale(1.03);
        }

        /* Cuadrícula de Pasos */
        .pasos-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
        }

        .paso-card {
            background: #f8fafc;
            padding: 2rem;
            border-radius: 12px;
            border-top: 5px solid var(--secondary);
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
            transition: var(--transition);
        }

        .paso-card:hover {
            transform: translateY(-5px);
            background: var(--white);
            box-shadow: var(--shadow);
        }

        .paso-numero {
            background: var(--primary);
            color: var(--white);
            width: 40px;
            height: 40px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.5rem;
            font-weight: bold;
            border-radius: 50%;
            margin-bottom: 1rem;
        }

        .paso-card h3 {
            margin: 0 0 1rem 0;
            color: var(--primary);
        }

        .paso-card p {
            margin: 0;
            color: var(--text-light);
            font-size: 0.95rem;
        }

        /* CALCULADORA DE INGRESOS CSS */
        .calc-container {
            background: linear-gradient(to right, #e2e8f0, #f8fafc);
            padding: 2rem;
            border-radius: 12px;
            border: 1px solid #cbd5e1;
        }

        .calc-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 1.5rem;
            margin-bottom: 2rem;
        }

        .input-group {
            display: flex;
            flex-direction: column;
        }

        .input-group label {
            font-weight: 600;
            margin-bottom: 0.5rem;
            color: var(--text-main);
        }

        .input-group input {
            padding: 0.8rem;
            font-size: 1rem;
            border: 2px solid #cbd5e1;
            border-radius: 8px;
            transition: var(--transition);
            font-family: 'Poppins', sans-serif;
        }

        .input-group input:focus {
            outline: none;
            border-color: var(--secondary);
            box-shadow: 0 0 0 3px rgba(26, 139, 108, 0.2);
        }

        .btn-calcular {
            background-color: var(--primary);
            color: var(--white);
            border: none;
            padding: 1rem 2rem;
            font-size: 1.1rem;
            font-weight: 600;
            border-radius: 8px;
            cursor: pointer;
            transition: var(--transition);
            width: 100%;
            font-family: 'Poppins', sans-serif;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        .btn-calcular:hover {
            background-color: #094031;
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(13, 92, 70, 0.4);
        }

        .resultados-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 1rem;
            margin-top: 2rem;
        }

        .resultado-box {
            background: var(--white);
            padding: 1.5rem;
            border-radius: 8px;
            text-align: center;
            box-shadow: 0 2px 10px rgba(0,0,0,0.05);
            border-bottom: 4px solid var(--accent);
        }

        .resultado-box h4 {
            margin: 0 0 0.5rem 0;
            color: var(--text-light);
            font-size: 0.9rem;
            text-transform: uppercase;
        }

        .resultado-box span {
            font-size: 1.8rem;
            font-weight: 700;
            color: var(--primary);
            word-break: break-all;
        }

        /* Sección Futuros Ingresos */
        .ingresos-card {
            background: #e6f4f1;
            padding: 2rem;
            border-left: 6px solid var(--primary);
            border-radius: 0 12px 12px 0;
            font-size: 1.1rem;
        }

        /* Sección de Contacto */
        .contacto-section {
            text-align: center;
            background: var(--text-main);
            color: var(--white);
        }

        .contacto-section h2 {
            color: var(--white);
            border-bottom-color: var(--accent);
        }

        .botones-contacto {
            display: flex;
            justify-content: center;
            gap: 1.5rem;
            flex-wrap: wrap;
            margin-top: 1.5rem;
        }

        .btn-contacto {
            display: inline-block;
            background: var(--accent);
            color: var(--text-main);
            text-decoration: none;
            padding: 1rem 2rem;
            font-size: 1.1rem;
            font-weight: 700;
            border-radius: 50px;
            transition: var(--transition);
        }

        .btn-contacto:hover {
            background: var(--white);
            transform: scale(1.05);
            box-shadow: 0 10px 20px rgba(255, 215, 0, 0.3);
        }

        .btn-whatsapp {
            background: #25D366;
            color: white;
        }

        .btn-whatsapp:hover {
            background: #128C7E;
            color: white;
            box-shadow: 0 10px 20px rgba(37, 211, 102, 0.3);
        }

        footer {
            text-align: center;
            padding: 2rem;
            color: var(--text-light);
            font-size: 0.9rem;
        }

        @media (max-width: 768px) {
            h1 { font-size: 2.5rem; }
            .container { margin-top: -1.5rem; padding: 0 1rem; }
            section { padding: 1.5rem; }
            .botones-contacto { flex-direction: column; }
        }
    </style>
</head>
<body>

    <header>
        <h1>Dinero en Internet: Tu Éxito</h1>
        <p>Estrategias y herramientas reales para generar ingresos (Enfocado en Colombia)</p>
    </header>

    <div class="container">
        
        <!-- Explicación -->
        <section id="explicacion">
            <h2>¿Cómo lograr los objetivos?</h2>
            <p>Generar ingresos en internet requiere dejar atrás los mitos y enfocarse en construir sistemas y adquirir habilidades de alto valor. Ya sea programando páginas web, diseñando, o creando contenido, el objetivo principal es ofrecer una solución a un mercado global. Con disciplina, podrás convertir tu tiempo y conocimiento en una fuente de ingresos real.</p>
            
            <div class="image-container">
                <!-- Imagen genérica de alta calidad garantizada que sí cargará -->
                <img src="https://images.unsplash.com/photo-1621252179027-94459d278660?q=80&w=1000&auto=format&fit=crop" alt="Billetes representando ingresos">
            </div>
        </section>

        <!-- Pasos a Seguir -->
        <section id="pasos">
            <h2>Pasos a seguir</h2>
            <div class="pasos-grid">
                <div class="paso-card">
                    <div class="paso-numero">1</div>
                    <h3>Elige tu Habilidad</h3>
                    <p>Enfócate en algo que el mercado necesite: Desarrollo Web (HTML, CSS, JS), Diseño Gráfico, o Marketing Digital.</p>
                </div>
                <div class="paso-card">
                    <div class="paso-numero">2</div>
                    <h3>Crea tu Portafolio</h3>
                    <p>Arma una página web profesional para mostrar lo que sabes hacer. Tu trabajo habla más que tu currículum.</p>
                </div>
                <div class="paso-card">
                    <div class="paso-numero">3</div>
                    <h3>Busca Clientes</h3>
                    <p>Usa plataformas como Upwork, Workana o contacta negocios locales que necesiten digitalizarse.</p>
                </div>
                <div class="paso-card">
                    <div class="paso-numero">4</div>
                    <h3>Escala tus Ingresos</h3>
                    <p>Una vez domines el trabajo freelance, crea productos digitales o agencias para multiplicar tus ganancias.</p>
                </div>
            </div>
        </section>

        <!-- CALCULADORA DE INGRESOS -->
        <section id="calculadora">
            <h2>Calculadora de Ingresos Freelance</h2>
            <p>Descubre cuánto podrías ganar cobrando por hora. <em>Ingresa los valores y haz clic en calcular.</em></p>
            
            <div class="calc-container">
                <div class="calc-grid">
                    <div class="input-group">
                        <label for="tarifa">Tarifa por Hora (COP)</label>
                        <input type="number" id="tarifa" placeholder="Ej: 25000" min="0">
                    </div>
                    <div class="input-group">
                        <label for="horas">Horas al día</label>
                        <input type="number" id="horas" placeholder="Ej: 4" min="0" max="24">
                    </div>
                    <div class="input-group">
                        <label for="dias">Días a la semana</label>
                        <input type="number" id="dias" placeholder="Ej: 5" min="0" max="7">
                    </div>
                </div>

                <button class="btn-calcular" onclick="calcularIngresos()">Calcular Mis Posibles Ingresos</button>

                <div class="resultados-grid">
                    <div class="resultado-box">
                        <h4>Ingreso Semanal</h4>
                        <span id="res-semanal">$0</span>
                    </div>
                    <div class="resultado-box">
                        <h4>Ingreso Mensual (Aprox)</h4>
                        <span id="res-mensual">$0</span>
                    </div>
                    <div class="resultado-box">
                        <h4>Ingreso Anual</h4>
                        <span id="res-anual">$0</span>
                    </div>
                </div>
            </div>
        </section>

        <!-- Futuros Ingresos -->
        <section id="ingresos">
            <h2>Proyección y Futuros Ingresos</h2>
            <div class="ingresos-card">
                <p>Al principio, tus ingresos dependerán directamente del tiempo que inviertas (<strong>ingresos activos</strong>). A medida que ganes experiencia en internet, podrás crear fuentes de <strong>ingresos pasivos</strong> (plantillas web, aplicaciones, cursos). Esto significa que tu código y tus productos digitales estarán trabajando y generando dinero (en pesos o dólares) incluso mientras duermes.</p>
            </div>
        </section>

        <!-- Sección de Contacto Personalizada -->
        <section id="contacto" class="contacto-section">
            <h2>¿Tienes dudas o necesitas un proyecto web?</h2>
            <p>Estoy disponible para peticiones, colaboraciones y desarrollo de páginas a medida.</p>
            <div class="botones-contacto">
                <!-- Enlace directo al correo -->
                <a href="mailto:yeisonxd_53@hotmail.com" class="btn-contacto">✉️ Enviar Correo</a>
                
                <!-- Enlace directo a WhatsApp con el número +57 -->
                <a href="https://wa.me/573161513389" target="_blank" class="btn-contacto btn-whatsapp">📱 WhatsApp: 316 151 3389</a>
            </div>
        </section>

    </div>

    <footer>
        <p>&copy; 2026 - Proyecto Web Creado con HTML, CSS y JS.</p>
    </footer>

    <!-- Lógica de la Calculadora en JavaScript -->
    <script>
        function calcularIngresos() {
            const tarifa = parseFloat(document.getElementById('tarifa').value) || 0;
            const horas = parseFloat(document.getElementById('horas').value) || 0;
            const dias = parseFloat(document.getElementById('dias').value) || 0;

            const semanal = tarifa * horas * dias;
            const mensual = semanal * 4.33; 
            const anual = semanal * 52;     

            const formatter = new Intl.NumberFormat('es-CO', {
                style: 'currency',
                currency: 'COP',
                minimumFractionDigits: 0,
                maximumFractionDigits: 0
            });

            document.getElementById('res-semanal').textContent = formatter.format(semanal);
            document.getElementById('res-mensual').textContent = formatter.format(mensual);
            document.getElementById('res-anual').textContent = formatter.format(anual);
            
            const cajas = document.querySelectorAll('.resultado-box');
            cajas.forEach(caja => {
                caja.style.transform = 'scale(1.05)';
                setTimeout(() => caja.style.transform = 'scale(1)', 200);
            });
        }
    </script>
</body>
</html>
