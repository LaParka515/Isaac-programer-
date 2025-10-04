<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>¡El Amor de Mi Vida!</title>
    <style>
        /* ESTILOS GENERALES Y FONDO ROMÁNTICO */
        body {
            font-family: 'Times New Roman', serif;
            background-color: #f7e0e7; /* Rosa muy suave */
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            margin: 0;
            text-align: center;
            padding: 20px;
        }

        /* Contenedor principal para centrar el contenido */
        .contenedor-mensaje {
            background-color: rgba(255, 255, 255, 0.9);
            padding: 50px;
            border-radius: 25px;
            box-shadow: 0 8px 30px rgba(255, 105, 180, 0.4); /* Sombra rosada más intensa */
            max-width: 700px;
            width: 90%;
        }

        /* TÍTULO ANIMADO (PULSACIÓN DE COLOR) */
        .titulo-animado {
            font-family: 'Brush Script MT', cursive; 
            font-size: 4em; /* Más grande */
            font-weight: bold;
            text-shadow: 1px 1px 4px rgba(0, 0, 0, 0.15);
            margin-bottom: 50px;
            /* Aplicación de la animación de color */
            animation: latido-color 4s infinite alternate-reverse; 
            color: #ff69b4; 
        }
        
        @keyframes latido-color {
            0% { 
                color: #ff69b4; /* Rosa Fuerte */
            }
            100% { 
                color: #e60073; /* Rosa Oscuro/Fucsia */
            }
        }

        /* ESTILO Y ANIMACIÓN DE LAS PREGUNTAS */
        .pregunta {
            font-size: 1.6em;
            color: #d63384; /* Rosa intenso */
            margin: 20px 0;
            opacity: 0; 
            transform: translateY(20px); 
            animation: aparecer-suave 1.3s ease-out forwards; /* Un poco más rápido */
        }

        /* Aplicación de retraso secuencial para 10 preguntas y 2 líneas de inicio */
        .pregunta:nth-child(2) { animation-delay: 1.0s; } 
        .pregunta:nth-child(3) { animation-delay: 2.3s; }
        .pregunta:nth-child(4) { animation-delay: 3.6s; }
        .pregunta:nth-child(5) { animation-delay: 4.9s; }
        .pregunta:nth-child(6) { animation-delay: 6.2s; }
        .pregunta:nth-child(7) { animation-delay: 7.5s; }
        .pregunta:nth-child(8) { animation-delay: 8.8s; }
        .pregunta:nth-child(9) { animation-delay: 10.1s; }
        .pregunta:nth-child(10) { animation-delay: 11.4s; }
        .pregunta:nth-child(11) { animation-delay: 12.7s; }
        .pregunta:nth-child(12) { animation-delay: 14.0s; }

        @keyframes aparecer-suave {
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        /* MENSAJE FINAL (MUY LARGO) */
        .mensaje-final {
            font-size: 1.5em; /* Un poco más pequeño para que quepa más texto */
            line-height: 1.6;
            font-style: italic;
            color: #880e4f; 
            margin-top: 60px;
            border-top: 3px solid #ffb3c1; 
            padding-top: 30px;
            opacity: 0;
            animation: aparecer-suave 2.5s ease-out forwards;
            animation-delay: 15.5s; /* Aparece después de todas las preguntas */
            text-align: justify; /* Justificado para verse como una carta */
        }
        
        .firma {
            display: block;
            margin-top: 25px;
            font-size: 1.2em;
            font-weight: bold;
            text-align: right;
            color: #c2185b;
        }
    </style>
</head>
<body>

    <div class="contenedor-mensaje">
        
        <h1 class="titulo-animado">¡A la persona que me robó el corazón! 💖</h1>
        
        <p class="pregunta">Necesito saber algo importante...</p>
        <p class="pregunta">¿Me **amas** hoy, mañana y siempre?</p>
        <p class="pregunta">¿Me **adoras** como yo te adoro a ti?</p>
        <p class="pregunta">¿Crees que nuestra **conexión** es mágica e irrompible?</p>
        <p class="pregunta">¿Soy el primer y el último **pensamiento** de tu día?</p>
        <p class="pregunta">¿Crees que podríamos **viajar** juntos por el resto de nuestras vidas?</p>
        <p class="pregunta">¿Prometes seguir creando **recuerdos inolvidables** a mi lado?</p>
        <p class="pregunta">¿Soy tu **lugar seguro** y tu aventura favorita?</p>
        <p class="pregunta">¿Te ves **sonriendo** a mi lado dentro de veinte años?</p>
        <p class="pregunta">¿Soy la **persona** que has estado esperando toda tu vida?</p>
        <p class="pregunta">¿Y me harás el inmenso favor de no **dejarme nunca**?</p>
        
        <p class="mensaje-final">
            Sé que para cada una de esas preguntas, la respuesta que tu alma grita es un rotundo y sincero **SÍ**. Y es esa certeza la que me hace el ser más afortunado/a del universo. Desde el momento en que llegaste a mi vida, todo se pintó de colores más brillantes, de melodías más dulces y de una paz que nunca antes había conocido. Eres mi **refugio**, mi **inspiración**, mi **compañero/a de sueños** y mi más hermosa realidad. No solo te amo por quien eres, sino por quien me permites ser cuando estoy contigo: mi mejor versión. Eres esa casualidad que se convirtió en la **prioridad** de mi vida. Gracias por cada risa, cada abrazo, cada mirada que me dice "aquí estoy y siempre estaré". Quiero despertar a tu lado, ver atardeceres contigo y enfrentar cada desafío de la vida, sabiendo que tú y yo, juntos, podemos con todo. Nunca olvides que mi amor por ti es **infinito**, **profundo** y **verdadero**.
            <span class="firma">Te amo, hoy y para siempre.</span>
        </p>
    </div>

</body>
</html>

