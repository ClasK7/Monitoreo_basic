# Plataforma de Gestión y Monitoreo Ambiental OpenAQ

## Descripción del Proyecto
Este dashboard interactivo permite visualizar y gestionar información de estaciones de monitoreo ambiental a nivel global. El sistema consume la API pública de OpenAQ V3 para extraer datos telemétricos en tiempo real y los ubica geográficamente mediante la API de Google Maps.

## Cumplimiento Estricto de Restricciones (Rúbrica)
De acuerdo a las restricciones especificadas en la rúbrica de evaluación, este proyecto fue desarrollado bajo una arquitectura estrictamente **Vanilla**:
- **Cero Frameworks JS:** No se utilizó React, Vue.js ni Angular. Toda la manipulación del DOM y el estado de la aplicación se gestiona con JavaScript Puro (Vanilla JS).
- **Cero Librerías Externas:** No se incluyeron librerías como Axios o jQuery. Las peticiones HTTP asíncronas se resuelven utilizando la API nativa `fetch()`.
- **Cero Librerías Gráficas:** Para cumplir con la restricción de "Solo HTML y CSS", la simulación de los gráficos de barras en el panel lateral se desarrolló creando contenedores dinámicos utilizando exclusivamente propiedades de CSS (Flexbox y cálculo de alturas en porcentajes), evitando el uso de herramientas como Chart.js.
- **Diseño sin Bootstrap:** La estructura de la interfaz (Sidebar, Cards, Tablas) fue construida desde cero con CSS Grid y Flexbox.

## Instrucciones de Uso
1. Clonar el repositorio o extraer los archivos en una carpeta local.
2. Abrir el archivo `index.html` en cualquier navegador web moderno (Chrome, Edge, Firefox).
3. No requiere instalación de dependencias (`npm install`) ni servidores de desarrollo locales (`npm run dev`) debido a su naturaleza nativa.

*Nota: Para el correcto funcionamiento geográfico, se requiere una conexión activa a internet para contactar los scripts de Google Maps y la red de OpenAQ.*