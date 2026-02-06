?? Simulador de Modulación Digital
?? Descripción del Proyecto

Aplicación web interactiva para visualizar y simular diferentes tipos de modulación digital: ASK, FSK, PSK y 4-QAM. Este simulador permite comprender visualmente cómo se representan las señales binarias en diferentes técnicas de modulación.
? Características Principales

    Modulaciones implementadas:

        ?? ASK (Amplitude Shift Keying)

        ?? FSK (Frequency Shift Keying)

        ?? PSK (Phase Shift Keying)

        ?? 4-QAM (Quadrature Amplitude Modulation)

    Visualizaciones:

        Señal en dominio del tiempo

        Diagrama de constelación

        Parámetros ajustables en tiempo real

        Separadores de bits en la señal temporal

    Controles interactivos:

        Entrada manual de secuencia binaria (hasta 16 bits)

        Generador de secuencias aleatorias

        Validación de entrada binaria

        Sliders para ajustar frecuencia, tasa de bits y amplitud

        Botones de inicio/pausa y reinicio

?? Cómo Usar la Aplicación
1. Configurar la secuencia binaria

    Ingresa una secuencia de 0s y 1s en el campo "Secuencia de bits"

    Usa el botón "Aleatorio" para generar una secuencia aleatoria

    Presiona "Validar" para confirmar que la entrada es correcta

2. Seleccionar el tipo de modulación

    Elige entre ASK, FSK, PSK o 4-QAM en el menú desplegable

    La información y fórmula se actualizarán automáticamente

3. Ajustar parámetros

    Frecuencia Portadora: 50-500 Hz

    Tasa de Bits: 1-10 bps

    Amplitud de Señal: 0.5-2.0

4. Visualizar resultados

    Observa la señal modulada en el gráfico temporal

    Examina el diagrama de constelación (aplicable para PSK y QAM)

    Presiona "Iniciar Simulación" para ver la animación

??? Tecnologías Utilizadas

    Frontend:

        HTML5

        CSS3 (Grid, Flexbox, Animaciones)

        JavaScript (Canvas API)

        Font Awesome 6.4.0 (iconos)

    Características técnicas:

        Diseño responsive (adaptable a móviles y tablets)

        Interfaz de usuario moderna con tema oscuro

        Gráficos en tiempo real usando Canvas

        Validación de entrada del usuario

?? Estructura del Proyecto
text

simulador-modulacion-digital/
¦
+-- app web premium.html  # Archivo principal (todo en uno)
¦
+-- README.md             # Este archivo
¦
+-- (posibles extensiones)
    +-- assets/           # Imágenes y recursos
    +-- css/              # Estilos separados
    +-- js/               # Scripts separados

?? Objetivos Educativos

Este simulador está diseñado para ayudar a estudiantes y profesionales a:

    Comprender visualmente las diferencias entre técnicas de modulación

    Observar cómo los parámetros afectan las señales moduladas

    Entender la relación entre bits y símbolos en QAM

    Analizar diagramas de constelación

    Experimentar con diferentes configuraciones

?? Autores

    Alejandro Marrero Rojas

    Sheyla Romy Lara Batista

Institución: Universidad de Oriente
Facultad: Ingenierías en Telecomunicaciones, Informática y Biomédica
Proyecto: Final de Aplicaciones Web
Año: 2024
?? Aspectos Técnicos de las Modulaciones
ASK (Modulación por Amplitud)

    Fórmula: s(t) = A·m(t)·cos(2pf0t)

    Bit '1': amplitud alta

    Bit '0': amplitud baja

FSK (Modulación por Frecuencia)

    Fórmula: s(t) = A·cos(2pf?t)

    Bit '1': frecuencia f1

    Bit '0': frecuencia f2 (70% de f1)

PSK (Modulación por Fase)

    Fórmula: s(t) = A·cos(2pf0t + f?)

    Bit '1': fase 0°

    Bit '0': fase 180°

4-QAM (Modulación en Cuadratura)

    Fórmula: s(t) = I·cos(2pf0t) - Q·sin(2pf0t)

    Cada símbolo representa 2 bits

    Puntos de constelación: 00, 01, 10, 11

?? Instalación y Ejecución

    Requisitos:

        Navegador web moderno (Chrome 90+, Firefox 88+, Edge 90+)

        No se requieren dependencias externas

    Ejecución local:

        Descarga el archivo app web premium.html

        Ábrelo directamente en tu navegador

        ¡Listo para usar!

    Despliegue web:

        Sube el archivo a cualquier servidor web estático

        Accede a través de la URL correspondiente

?? Compatibilidad

    Desktop: Chrome, Firefox, Safari, Edge

    Móvil: iOS Safari, Android Chrome

    Tablet: iPad, Android tablets

?? Paleta de Colores

    Fondo principal: #0a192f (azul oscuro)

    Acento principal: #64ffda (verde cian)

    Texto principal: #e6f1ff (blanco azulado)

    Texto secundario: #8892b0 (gris azulado)

    Contenedores: #112240 (azul medio)

    Bordes: #233554 (azul claro)

? Optimizaciones

    Rendimiento: Uso eficiente de requestAnimationFrame

    Responsive: Diseño adaptable con Grid y media queries

    Accesibilidad: Contraste adecuado, etiquetas descriptivas

    Mantenibilidad: Código estructurado y comentado

?? Posibles Mejoras Futuras

    Características técnicas:

        Agregar ruido AWGN para simulación de canal

        Calcular BER (Bit Error Rate)

        Implementar más modulaciones (8-PSK, 16-QAM)

        Exportar gráficos como PNG/PDF

    Funcionalidades educativas:

        Tutorial paso a paso

        Ejercicios prácticos

        Comparación lado a lado

        Explicaciones detalladas

    Mejoras de UI/UX:

        Modo claro/oscuro

        Internacionalización (inglés/español)

        Panel de estadísticas

        Historial de simulaciones

?? Licencia

© 2024 - Simulador de Modulación Digital
Proyecto académico - Universidad de Oriente
Desarrollado con fines educativos
?? Contribuciones

Este es un proyecto académico cerrado. Para sugerencias o consultas, contactar a los autores.