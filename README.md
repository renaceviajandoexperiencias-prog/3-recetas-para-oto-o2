<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Recetas Ayurvédicas para el Otoño</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&family=Montserrat:wght@400;600;700&display=swap');
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Montserrat', sans-serif;
            line-height: 1.6;
            color: #333;
            background: #fff;
        }
        
        .pdf-page {
            max-width: 800px;
            margin: 0 auto;
            padding: 80px 50px;
            min-height: 100vh;
            background: white;
        }
        
        .cover {
            text-align: center;
            padding: 100px 40px;
            background: linear-gradient(135deg, #8B6F47 0%, #D4A574 50%, #CD8C5C 100%);
            color: white;
            border-radius: 20px;
            margin-bottom: 80px;
        }
        
        .cover h1 {
            font-family: 'Playfair Display', serif;
            font-size: 52px;
            margin-bottom: 20px;
            line-height: 1.2;
        }
        
        .cover .subtitle {
            font-size: 24px;
            font-weight: 600;
            margin-bottom: 40px;
            opacity: 0.95;
        }
        
        .cover .emoji {
            font-size: 80px;
            margin-bottom: 30px;
        }
        
        .cover .footer-text {
            font-size: 18px;
            margin-top: 50px;
            opacity: 0.9;
            font-style: italic;
        }
        
        .intro-box {
            background: linear-gradient(135deg, #FFF8F0 0%, #F5E6D3 100%);
            padding: 50px 40px;
            border-radius: 15px;
            margin-bottom: 60px;
            border-left: 6px solid #8B6F47;
        }
        
        .intro-box p {
            font-size: 17px;
            line-height: 1.8;
            margin-bottom: 15px;
            color: #555;
        }
        
        .intro-box strong {
            color: #8B6F47;
        }
        
        .recipe-card {
            background: white;
            border: 2px solid #D4A574;
            border-radius: 15px;
            padding: 40px;
            margin-bottom: 40px;
            page-break-inside: avoid;
        }
        
        .recipe-card h2 {
            font-family: 'Playfair Display', serif;
            font-size: 32px;
            color: #8B6F47;
            margin-bottom: 10px;
            display: flex;
            align-items: center;
            gap: 15px;
        }
        
        .recipe-card .emoji {
            font-size: 40px;
        }
        
        .recipe-info {
            display: flex;
            gap: 30px;
            margin-bottom: 25px;
            font-size: 15px;
            color: #666;
            flex-wrap: wrap;
        }
        
        .recipe-info span {
            display: flex;
            align-items: center;
            gap: 8px;
        }
        
        .recipe-section h3 {
            color: #D4A574;
            font-size: 18px;
            font-weight: 700;
            margin-top: 25px;
            margin-bottom: 12px;
        }
        
        .recipe-section ul {
            list-style: none;
            margin-left: 0;
        }
        
        .recipe-section li {
            padding-left: 25px;
            margin-bottom: 10px;
            position: relative;
            font-size: 15px;
            line-height: 1.7;
            color: #555;
        }
        
        .recipe-section li::before {
            content: '✦';
            position: absolute;
            left: 0;
            color: #D4A574;
            font-size: 16px;
        }
        
        .benefits {
            background: #FFFAEF;
            padding: 20px;
            border-radius: 10px;
            margin-top: 20px;
        }
        
        .benefits strong {
            color: #8B6F47;
            display: block;
            margin-bottom: 8px;
        }
        
        .benefits p {
            font-size: 14px;
            color: #666;
            line-height: 1.6;
            margin: 0;
        }
        
        .tips-box {
            background: linear-gradient(135deg, #FFF5E6 0%, #F5E6D3 100%);
            padding: 40px;
            border-radius: 15px;
            margin: 60px 0;
            border-left: 5px solid #D4A574;
        }
        
        .tips-box h2 {
            font-family: 'Playfair Display', serif;
            font-size: 28px;
            color: #8B6F47;
            margin-bottom: 25px;
        }
        
        .tip-item {
            margin-bottom: 20px;
            padding-left: 30px;
            position: relative;
        }
        
        .tip-item::before {
            content: '🍂';
            position: absolute;
            left: 0;
            font-size: 20px;
        }
        
        .tip-item h4 {
            color: #8B6F47;
            font-size: 16px;
            font-weight: 700;
            margin-bottom: 5px;
        }
        
        .tip-item p {
            font-size: 14px;
            color: #666;
            line-height: 1.6;
        }
        
        .quote {
            text-align: center;
            font-size: 22px;
            font-style: italic;
            color: #8B6F47;
            margin: 60px 0;
            padding: 40px;
            border-top: 3px solid #D4A574;
            border-bottom: 3px solid #D4A574;
        }
        
        .cta-final {
            background: linear-gradient(135deg, #8B6F47 0%, #D4A574 50%, #CD8C5C 100%);
            color: white;
            padding: 50px 40px;
            border-radius: 15px;
            text-align: center;
            margin-top: 60px;
        }
        
        .cta-final h2 {
            font-family: 'Playfair Display', serif;
            font-size: 32px;
            margin-bottom: 20px;
        }
        
        .cta-final p {
            font-size: 17px;
            line-height: 1.8;
            margin-bottom: 15px;
        }
        
        .cta-details {
            background: rgba(255,255,255,0.2);
            padding: 25px;
            border-radius: 12px;
            margin: 25px 0;
        }
        
        .cta-details p {
            font-size: 16px;
            margin: 10px 0;
            font-weight: 600;
        }
        
        .contact-info {
            margin-top: 25px;
            font-size: 15px;
        }
        
        .contact-info p {
            margin: 8px 0;
        }
        
        .footer {
            text-align: center;
            margin-top: 60px;
            padding-top: 40px;
            border-top: 2px solid #D4A574;
            font-size: 14px;
            color: #666;
        }
        
        @media print {
            body {
                background: white;
            }
            .pdf-page {
                padding: 40px 30px;
            }
        }
    </style>
</head>
<body>
    <div class="pdf-page">
        <!-- PORTADA -->
        <div class="cover">
            <div class="emoji">🍂</div>
            <h1>Recetas Ayurvédicas<br>para el Otoño</h1>
            <div class="subtitle">Infusiones que calman, leche dorada y recetas sencillas</div>
            <div class="footer-text">Transforma tu otoño a través de la alimentación consciente</div>
        </div>
        
        <!-- INTRODUCCIÓN -->
        <div class="intro-box">
            <p><strong>¿Sabías que el otoño es la estación del cambio?</strong></p>
            <p>Según Ayurveda, el otoño aumenta el dosha Vata (aire y movimiento). Esto puede dejarte dispersa, ansiosa, o con energía inestable. Pero aquí está la magia: <strong>a través de la comida podemos encontrar equilibrio</strong>.</p>
            <p>Las recetas que compartimos aquí son sencillas, con ingredientes que encuentras en cualquier supermercado, y están diseñadas para calmarte, nutrirte y preparar tu cuerpo para los cambios de esta estación.</p>
            <p><strong>No necesitas ser experta en cocina. Solo necesitas ganas de cuidarte.</strong></p>
        </div>
        
        <!-- RECETA 1: LECHE DORADA -->
        <div class="recipe-card">
            <h2><span class="emoji">🥛</span>Leche Dorada (Golden Milk)</h2>
            <div class="recipe-info">
                <span>⏱️ 10 minutos</span>
                <span>🔥 1 taza (250ml)</span>
                <span>💛 Calmante & Antiinflamatorio</span>
            </div>
            
            <div class="recipe-section">
                <h3>Ingredientes</h3>
                <ul>
                    <li>1 taza de leche (puede ser de vaca, almendra o avena)</li>
                    <li>½ cucharadita de cúrcuma en polvo</li>
                    <li>¼ cucharadita de gengibre fresco rallado</li>
                    <li>1 pizca de pimienta negra</li>
                    <li>½ cucharadita de canela</li>
                    <li>½ cucharadita de miel (agregar al final)</li>
                    <li>Pizca de sal marina</li>
                </ul>
            </div>
            
            <div class="recipe-section">
                <h3>Preparación</h3>
                <ul>
                    <li>Calienta la leche en una olla a fuego medio (sin dejar hervir)</li>
                    <li>Agrega la cúrcuma, gengibre, pimienta y canela</li>
                    <li>Remueve bien durante 3-5 minutos hasta que se disuelva todo</li>
                    <li>Vierte en una taza y deja enfriar 2 minutos</li>
                    <li>Agrega la miel y mezcla</li>
                    <li>Bebe lentamente, observando cada sorbo</li>
                </ul>
            </div>
            
            <div class="benefits">
                <strong>✨ Beneficios Ayurvédicos:</strong>
                <p>La cúrcuma reduce la inflamación y calma el Vata. El gengibre ayuda a la digestión. La canela estabiliza el azúcar. La pimienta mejora la absorción de la cúrcuma.</p>
            </div>
            
            <div class="benefits" style="margin-top: 15px;">
                <strong>💡 Consejo:</strong>
                <p>Bébela por la noche, 30 minutos antes de dormir. Te ayudará a conciliar el sueño más fácilmente.</p>
            </div>
        </div>
        
        <!-- RECETA 2: INFUSIÓN CALMANTE -->
        <div class="recipe-card">
            <h2><span class="emoji">🫖</span>Infusión de Calma Otoñal</h2>
            <div class="recipe-info">
                <span>⏱️ 5 minutos</span>
                <span>🔥 1 taza</span>
                <span>🧘‍♀️ Relajante & Equilibrante</span>
            </div>
            
            <div class="recipe-section">
                <h3>Ingredientes</h3>
                <ul>
                    <li>1 bolsa de té de manzanilla (o 1 cucharada de flores secas)</li>
                    <li>1 rama de canela</li>
                    <li>2-3 hojitas de menta fresca (opcional)</li>
                    <li>1 rodaja fina de jengibre fresco</li>
                    <li>250ml de agua caliente</li>
                    <li>Miel al gusto</li>
                </ul>
            </div>
            
            <div class="recipe-section">
                <h3>Preparación</h3>
                <ul>
                    <li>Calienta agua hasta que casi hierva</li>
                    <li>Vierte en una taza con la manzanilla, canela, menta y jengibre</li>
                    <li>Tapa y deja reposar 5-7 minutos</li>
                    <li>Cuela y agrega miel</li>
                    <li>Respira el vapor durante 30 segundos antes de beber</li>
                    <li>Bebe con presencia y gratitud</li>
                </ul>
            </div>
            
            <div class="benefits">
                <strong>✨ Beneficios Ayurvédicos:</strong>
                <p>La manzanilla calma el sistema nervioso y reduce la ansiedad. La canela estabiliza emociones. El jengibre mejora la digestión. Perfecta para después de comer o antes de meditación.</p>
            </div>
        </div>
        
        <!-- RECETA 3: ARROZ CON VERDURAS OTOÑALES -->
        <div class="recipe-card">
            <h2><span class="emoji">🍚</span>Arroz Basmati con Verduras Otoñales</h2>
            <div class="recipe-info">
                <span>⏱️ 20 minutos</span>
                <span>🔥 2 porciones</span>
                <span>🥗 Nutritivo & Fácil de digerir</span>
            </div>
            
            <div class="recipe-section">
                <h3>Ingredientes</h3>
                <ul>
                    <li>1 taza de arroz basmati (lavado)</li>
                    <li>2 tazas de agua o caldo de verduras</li>
                    <li>½ calabaza pequeña cortada en cubos</li>
                    <li>1 zanahoria cortada en tiras</li>
                    <li>1 rama de apio cortada fina</li>
                    <li>½ cucharadita de comino</li>
                    <li>½ cucharadita de cúrcuma</li>
                    <li>1 cucharada de ghee (mantequilla clarificada) o aceite</li>
                    <li>Sal marina al gusto</li>
                </ul>
            </div>
            
            <div class="recipe-section">
                <h3>Preparación</h3>
                <ul>
                    <li>Calienta el ghee en una olla a fuego medio</li>
                    <li>Agrega las semillas de comino y espera a que hagan "pop"</li>
                    <li>Añade la calabaza, zanahoria y apio. Saltea 5 minutos</li>
                    <li>Agrega la cúrcuma y mezcla bien</li>
                    <li>Incorpora el arroz y remueve durante 1 minuto</li>
                    <li>Vierte el agua/caldo y lleva a ebullición</li>
                    <li>Baja el fuego, tapa y cocina 15 minutos hasta que el arroz absorba el líquido</li>
                    <li>Reposa 3 minutos antes de servir</li>
                </ul>
            </div>
            
            <div class="benefits">
                <strong>✨ Beneficios Ayurvédicos:</strong>
                <p>El arroz basmati es fácil de digerir. La calabaza y zanahoria nutren sin pesadez. El ghee facilita la absorción de nutrientes. Ideal para el almuerzo otoñal.</p>
            </div>
        </div>
        
        <!-- TIPS IMPORTANTES -->
        <div class="tips-box">
            <h2>3 Consejos Ayurvédicos para el Otoño</h2>
            
            <div class="tip-item">
                <h4>Come Cálido, Especiado y Húmedo</h4>
                <p>El otoño es frío y seco. Las comidas calientes, con especias (canela, comino, cúrcuma) y grasas saludables (ghee, aceite de coco) equilibran esta energía.</p>
            </div>
            
            <div class="tip-item">
                <h4>Come Despacio y Sentada</h4>
                <p>Mastica bien. El 80% de la digestión ocurre en la boca. Comer con prisa aumenta Vata y causa ansiedad. Come en silencio o con conversaciones agradables.</p>
            </div>
            
            <div class="tip-item">
                <h4>Respeta los Horarios</h4>
                <p>El otoño ama la rutina. Come a las mismas horas cada día. Desayuna ligero, almuerza fuerte (es tu comida principal), cena temprano y ligera.</p>
            </div>
        </div>
        
        <div class="quote">
            "La comida no es solo nutrición.<br>Es medicina. Es presencia. Es amor por ti misma."
        </div>
        
        <!-- CTA FINAL -->
        <div class="cta-final">
            <h2>Vive esto en Profundidad</h2>
            <p>Estas recetas son un primer paso. Pero imagina aprender directamente de expertos, preparar estas comidas juntas, y descubrir cómo el otoño puede ser tu aliado para transformarte.</p>
            
            <div class="cta-details">
                <p>🍂 <strong>Retiro Respira Otoño</strong></p>
                <p>📅 <strong>28-30 de Noviembre</strong></p>
                <p>🧘‍♀️ Yoga + Meditación + Automasaje + Cocina Consciente</p>
                <p>👭 Máximo 8 mujeres</p>
            </div>
            
            <p>¿Quieres profundizar en este camino?</p>
            
            <div class="contact-info">
                <p>📧 <strong>info@renaceviajandoexperiencias.com</strong></p>
                <p>📱 <strong>WhatsApp: 623 211 438</strong></p>
            </div>
        </div>
        
        <!-- FOOTER -->
        <div class="footer">
            <p><strong>Recuerda:</strong> Estas recetas son un regalo. Úsalas, comparte, disfruta.</p>
            <p style="margin-top: 20px;">Con amor y presencia,</p>
            <p><strong>Tu compañera de transformación 🍂</strong></p>
        </div>
    </div>

    <script>
        // Permitir descarga como PDF
        window.print = function() {
            window.print();
        };
    </script>
</body>
</html>
