# Plataforma de Gestión y Monitoreo Ambiental (Maqueta Estática)

## Descripción del Proyecto
Este proyecto es una maqueta web (mockup) estática para un dashboard de monitoreo ambiental. La interfaz ha sido diseñada para visualizar la disposición teórica de estaciones de monitoreo, métricas globales de la calidad del aire (basadas en la estructura de datos de OpenAQ), y el estado de la red IoT. 

## Cumplimiento Estricto de Restricciones (Rúbrica)
Para alinearse de manera estricta con las indicaciones académicas de este entregable, el proyecto fue desarrollado bajo las siguientes restricciones de diseño puro:
- **Solo HTML y CSS (Cero JavaScript):** La estructura y el diseño se construyeron sin ningún tipo de lógica de programación, frameworks (React/Vue) ni scripts nativos (Vanilla JS).
- **Cero Librerías Externas de Estilos:** No se utilizaron frameworks CSS como Bootstrap o Tailwind. Toda la responsividad y disposición del panel (Sidebar, Cards, Tablas) fue construida desde cero utilizando propiedades nativas como **CSS Grid** y **Flexbox**.
- **Visualización Geográfica Estática:** En lugar de consumir la API interactiva de Google Maps mediante JavaScript, se integró un componente `<iframe>` embebido estático que cumple con el requerimiento visual sin romper la regla de no usar scripts.
- **Gráficos Puros en CSS:** Para el requerimiento de los gráficos resumidos (histórico de 24h), se diseñó un contenedor de barras simuladas utilizando únicamente divisiones (`<div>`) con porcentajes de altura aplicados directamente por estilos CSS, descartando por completo librerías como Chart.js.

## Estructura de Archivos
- `index.html`: Contiene toda la semántica web, el esqueleto del panel y los datos insertados manualmente (hardcodeados) para simular la vista del usuario final.
- `styles.css`: Contiene las reglas de diseño, variables de color, tipografía y la estructura de grillas para organizar el dashboard.

## Instrucciones de Uso
1. Extraer los archivos (`index.html` y `styles.css`) en un directorio local.
2. Hacer doble clic sobre el archivo `index.html` para abrirlo en cualquier navegador web moderno (Chrome, Edge, Firefox, Safari).
3. Al ser un diseño 100% estático, **no requiere** de un servidor local, instalación de dependencias ni conexión activa a APIs externas para su renderizado principal.