# Juego del Ahorcado

## Descripción del Proyecto
Este repositorio contiene una implementación web interactiva del clásico "Juego del Ahorcado". El objetivo principal de la aplicación es ofrecer un pasatiempo de adivinanza de palabras (enfocado en nombres populares) a través de una interfaz de usuario atractiva y fácil de usar.

## Problema que Resuelve
El proyecto soluciona la necesidad de contar con un juego rápido y accesible desde cualquier navegador web sin necesidad de descargas o instalaciones de software adicional. Proporciona una forma interactiva de mejorar el vocabulario, practicar la ortografía y ofrecer entretenimiento casual. Además, sirve como un ejemplo práctico de manipulación del DOM y manejo de eventos en aplicaciones frontend puras.

## Funcionalidades Principales
- **Jugar al Ahorcado:** Los usuarios pueden intentar adivinar la palabra oculta seleccionando letras a través de un teclado en pantalla o usando su teclado físico.
- **Agregar Nuevas Palabras:** Permite a los usuarios expandir el diccionario de juego añadiendo sus propias palabras personalizadas antes de iniciar una partida.
- **Visualización Dinámica:** El juego dibuja las partes del ahorcado progresivamente con cada error cometido, además de registrar las letras incorrectas introducidas.
- **Estados de Juego:** Detecta automáticamente las condiciones de victoria o derrota, mostrando los mensajes correspondientes al usuario.

## Tecnologías Utilizadas
El proyecto ha sido desarrollado utilizando tecnologías fundamentales del desarrollo web frontend, sin dependencias de frameworks externos:
- **HTML5:** Para la estructura semántica de la aplicación y la disposición de los diferentes elementos.
- **CSS3:** Para el diseño visual, manejo de estructuras responsivas utilizando Flexbox y Grid, y el dibujo interactivo de las partes del ahorcado mediante hojas de estilo.
- **JavaScript (Vanilla JS):** Para la lógica del juego, la captura de eventos del teclado (físico y virtual) y la manipulación del Document Object Model (DOM).

## Instrucciones de Uso
1. **Clonar el repositorio:**
   Descargue los archivos locales mediante el siguiente comando en su terminal:
   `git clone https://github.com/Ibanezcalper/Juego-del-Ahorcado.git`
2. **Ejecutar la aplicación:**
   No se requiere de un servidor o entorno de desarrollo complejo. Simplemente abra el archivo `index.html` en su navegador web de preferencia (como Google Chrome, Mozilla Firefox, o Safari).
3. **Mecánica de Juego:**
   - En la pantalla de inicio, seleccione "JUGAR" para comenzar una partida.
   - Presione las letras en su teclado físico o haga clic en las teclas virtuales en pantalla para intentar adivinar la palabra oculta.
   - Si desea añadir nuevos términos al juego, seleccione "AGREGAR PALABRA" desde el menú principal.
