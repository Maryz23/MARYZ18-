<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LaMaryz18 - Edición de Videos Profesional</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #C92C3D 0%, #82292E 100%);
            min-height: 100vh;
            color: white;
            overflow-x: hidden;
        }
        
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
        }
        
        .header {
            text-align: center;
            margin-bottom: 40px;
            animation: fadeInDown 1s ease-out;
        }
        
        .logo {
            width: 120px;
            height: 120px;
            background: white;
            border-radius: 50%;
            margin: 0 auto 20px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 48px;
            font-weight: bold;
            color: #C92C3D;
            box-shadow: 0 8px 32px rgba(0,0,0,0.3);
            animation: pulse 2s infinite;
        }
        
        .main-title {
            font-size: 2.5rem;
            font-weight: bold;
            margin-bottom: 10px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
            background: linear-gradient(45deg, #ffffff, #f0f0f0);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }
        
        .subtitle {
            font-size: 1.2rem;
            color: #f0f0f0;
            margin-bottom: 30px;
        }
        
        .content-grid {
            display: grid;
            grid-template-columns: 1fr;
            gap: 30px;
            width: 100%;
            animation: fadeInUp 1s ease-out 0.3s both;
        }
        
        .card {
            background: rgba(255,255,255,0.1);
            backdrop-filter: blur(10px);
            border-radius: 20px;
            padding: 30px;
            border: 1px solid rgba(255,255,255,0.2);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        
        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 40px rgba(0,0,0,0.3);
        }
        
        .card-title {
            font-size: 1.5rem;
            font-weight: bold;
            margin-bottom: 15px;
            color: #30A3E0;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .card-content {
            font-size: 1rem;
            line-height: 1.6;
            color: #f0f0f0;
        }
        
        .services-list {
            list-style: none;
            margin-top: 15px;
        }
        
        .services-list li {
            margin-bottom: 8px;
            padding-left: 25px;
            position: relative;
        }
        
        .services-list li:before {
            content: "🎬";
            position: absolute;
            left: 0;
        }
        
        .contact-section {
            background: rgba(255,255,255,0.15);
            border-radius: 20px;
            padding: 30px;
            text-align: center;
            margin-top: 30px;
            animation: fadeInUp 1s ease-out 0.6s both;
        }
        
        .phone-number {
            font-size: 1.8rem;
            font-weight: bold;
            color: #30A3E0;
            margin-bottom: 10px;
            letter-spacing: 2px;
        }
        
        .instagram-handle {
            font-size: 1.2rem;
            color: #f0f0f0;
        }
        
        .cta-button {
            background: linear-gradient(45deg, #30A3E0, #4A90D9);
            color: white;
            padding: 15px 30px;
            border: none;
            border-radius: 50px;
            font-size: 1.1rem;
            font-weight: bold;
            margin-top: 20px;
            cursor: pointer;
            transition: all 0.3s ease;
            text-decoration: none;
            display: inline-block;
        }
        
        .cta-button:hover {
            transform: translateY(-2px);
            box-shadow: 0 10px 25px rgba(48,163,224,0.4);
        }
        
        .testimonial {
            background: rgba(255,255,255,0.08);
            border-left: 4px solid #30A3E0;
            padding: 20px;
            margin: 20px 0;
            border-radius: 10px;
            font-style: italic;
        }
        
        @keyframes fadeInDown {
            from {
                opacity: 0;
                transform: translateY(-30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
        
        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
        
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.05); }
            100% { transform: scale(1); }
        }
        
        @media (max-width: 768px) {
            .container {
                padding: 15px;
            }
            
            .main-title {
                font-size: 2rem;
            }
            
            .card {
                padding: 20px;
            }
            
            .phone-number {
                font-size: 1.5rem;
            }
        }
        
        .shine {
            position: relative;
            overflow: hidden;
        }
        
        .shine:before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255,255,255,0.3), transparent);
            animation: shine 3s infinite;
        }
        
        @keyframes shine {
            0% { left: -100%; }
            100% { left: 100%; }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <div class="logo shine">LM</div>
            <h1 class="main-title">LaMaryz18</h1>
            <p class="subtitle">Edición de Videos Profesional para Redes Sociales</p>
        </div>
        
        <div class="content-grid">
            <div class="card">
                <h2 class="card-title">🎯 Mi Especialidad</h2>
                <div class="card-content">
                    <p>Transformo tus ideas en contenido visual impactante que conecta con tu audiencia y genera engagement real en Instagram.</p>
                    <ul class="services-list">
                        <li>Edición profesional para Instagram</li>
                        <li>Creación de contenido viral</li>
                        <li>Transiciones cinematográficas</li>
                        <li>Color grading profesional</li>
                        <li>Audio y música personalizada</li>
                    </ul>
                </div>
            </div>
            
            <div class="card">
                <h2 class="card-title">💼 Para Mis Clientes</h2>
                <div class="card-content">
                    <p><strong>Trabajo con creadores de contenido, influencers y marcas</strong> que buscan:</p>
                    <ul class="services-list">
                        <li>Aumentar su alcance en redes</li>
                        <li>Crear contenido que vende</li>
                        <li>Mejorar su imagen profesional</li>
                        <li>Optimizar para algoritmos</li>
                    </ul>
                    <div class="testimonial">
                        "Cada video que edito está pensado para maximizar el engagement y generar resultados reales para tu marca."
                    </div>
                </div>
            </div>
            
            <div class="card">
                <h2 class="card-title">🚀 Resultados que Entrego</h2>
                <div class="card-content">
                    <ul class="services-list">
                        <li>Videos que aumentan visualizaciones 300%</li>
                        <li>Contenido optimizado para el algoritmo</li>
                        <li>Estilo único y profesional</li>
                        <li>Entrega rápida y de calidad</li>
                        <li>Asesoramiento en tendencias</li>
                    </ul>
                </div>
            </div>
        </div>
        
        <div class="contact-section">
            <div class="phone-number">0424-345-6508</div>
            <div class="instagram-handle">@lamaryz18</div>
            <a href="https://wa.me/584243456508" class="cta-button">Contactar Ahora</a>
        </div>
    </div>
</body>
</html>
