# Creador Flow v3

Gemini brings professional, prompt-based photo editing to your fingertips.

Creador Flow v3 es una aplicación web avanzada que utiliza inteligencia artificial para permitir ediciones de fotos profesionales mediante lenguaje natural.

## Características Principales

*   **Edición Localizada (Retouch):** Realiza ediciones precisas en áreas específicas de la imagen simplemente haciendo clic y describiendo el cambio deseado.
*   **Filtros Inteligentes:** Aplica estilos visuales y filtros complejos mediante descripciones de texto.
*   **Ajustes Pro:** Realiza ajustes de iluminación, color y otros parámetros de imagen mediante comandos de IA.
*   **Herramientas de Recorte:** Recorta y ajusta composiciones de manera precisa.
*   **Interfaz Fluida:** Diseño minimalista, oscuro y profesional, optimizado para la productividad, con transiciones de página suaves y animaciones de UI.

## Stack Tecnológico

*   **Frontend:** React 19 con TypeScript, optimizado con Vite.
*   **Estilos:** Tailwind CSS para un diseño limpio, moderno y responsivo.
*   **Animaciones:** `motion` para transiciones de estado fluidas y una experiencia de usuario altamente interactiva.
*   **Edición de Imagen:** `react-image-crop` para selección de áreas y API de Canvas nativa para procesado local.
*   **Inteligencia Artificial:** SDK oficial `@google/genai` para interactuar con los modelos de Google Gemini.

## Configuración y Requisitos

La aplicación requiere acceso a la API de Gemini para procesar las ediciones.

*   **API Key:** Se requiere la variable de entorno `GEMINI_API_KEY`. (Declarada en el archivo `.env.local`).
*   **Entorno:** Configurado para un entorno de compilación moderno bajo Vite, utilizando TypeScript ESNext.
*   **Diseño:** Tema oscuro forzado con tipografía Inter para una legibilidad máxima y un aspecto profesional.

---
*Desarrollado en Google AI Studio.*
