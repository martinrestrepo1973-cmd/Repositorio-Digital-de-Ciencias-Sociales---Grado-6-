# Repositorio Digital de Ciencias Sociales - Grado 6

Pequeño proyecto estático que reproduce la maqueta solicitada: barra superior con logo y búsqueda, menú lateral con categorías y tipos de recursos, lista de resultados de búsqueda y botones para "Subir nuevo recurso" y "Evaluar recurso".

Contenido del repositorio:
- index.html: interfaz principal
- assets/css/styles.css: estilos
- assets/js/app.js: lógica de búsqueda y renderizado
- assets/data/resources.json: datos de ejemplo de recursos
- .gitignore, LICENSE

Cómo ejecutar localmente:
1. Clona o descarga este repositorio.
2. Abre `index.html` en un navegador moderno. (Opcional: servir con un servidor local: `python -m http.server` y abrir http://localhost:8000)

Estructura de ejemplo de resultados:
- Cada recurso contiene: tipo (Infografía, Video, Texto, Taller), título, autor, nivel, valoración y archivos (url).

Notas:
- Proyecto está pensado como prototipo estático. La carga de recursos y la evaluación son simuladas (botones sin backend).
- Para integrarlo en una aplicación real, añade endpoints de API para búsquedas, subida de recursos y sistema de evaluación.

Licencia: MIT
