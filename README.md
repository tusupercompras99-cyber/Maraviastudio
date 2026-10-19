# Maravia Studio

Sitio independiente para el estudio de tecnología turística Maravia Studio. Desarrollado con HTML, CSS y JavaScript, sin dependencias de compilación.

## Vista local

Ejecutar `python3 -m http.server 8080 --directory dist` y abrir http://localhost:8080.

## Despliegue en Vercel

Importar el repositorio, seleccionar **Other** como framework, dejar el comando de compilación vacío y usar `dist` como directorio de salida. `vercel.json` incluye esa configuración.

## Contenido

- Identidad de Maravia: azul #043166, durazno #EDC0A2, naranja #FD9840, verde #145C47 y turquesa #26B6A5.
- Solución CORE 1: reservas personalizadas, pagos fraccionados y administración.
- Interfaces y aplicaciones demostrativas: no representan clientes ni reservas reales.
- Contacto: Instagram @somosmaravia. No se agregó un número de WhatsApp porque no fue proporcionado.
- Fotografías: Unsplash, IDs photo-1507525428034-b723cf961d3e y photo-1476514525535-07fb3b4ae5f1; ilustrativas, sin atribución a destinos específicos.
- Logotipos proporcionados por el usuario. No se modificó TI Web Agency.

## Actualizar dominio y contacto

Al conectar maravia.app, sustituir el origen de Sites en canonical, Open Graph, JSON-LD y sitemap.xml. Los enlaces de contacto se pueden cambiar por un enlace de WhatsApp verificado.

## Estructura

`dist/index.html`, `dist/styles.css`, `dist/app.js`, `dist/assets/` y archivos SEO. `.openai/hosting.json` corresponde exclusivamente al despliegue en Sites.
