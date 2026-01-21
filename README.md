## 🍎 Bad Apple // Kinetic Particles

Una experiencia visual interactiva que transforma el icónico video musical "Bad Apple!!" en un sistema dinámico de partículas cinéticas. Este proyecto procesa frames en tiempo real para dirigir miles de puntos de luz mediante leyes de física simulada.

✨ Características Principales

  Análisis de Frames en Tiempo Real: Procesa la luminancia de cada frame del video para determinar la posición de las partículas.

  Física de Partículas: Implementación de vectores de velocidad, fricción y atracción elástica (easing).

  Control de Experiencia:

  Sensibilidad (Threshold): Ajusta el umbral de detección de silueta.

  Densidad: Modifica la cantidad de partículas activas (soporta 15,000+).

  Diseño: Interfaz minimalista con efectos de desenfoque y Tailwind CSS.

🛠️ Stack Técnico

  HTML5 Canvas: Renderizado de alta frecuencia.

  JavaScript (Vanilla): Motor de física y manipulación de ImageData.

  Tailwind CSS: Estilizado de la UI.

🧠 ¿Cómo funciona?

  Downsampling: El video se proyecta en un canvas oculto de baja resolución (160x120) para optimizar el análisis.

  Análisis: Se escanea el brillo de los píxeles; si supera el umbral, se activa una coordenada de destino.

  Cinética: Las partículas viajan hacia los puntos activos con suavizado elástico, o flotan orgánicamente si no hay silueta.

⚖️ Licencia y Atribución

  Este proyecto ha sido generado íntegramente mediante herramientas de Inteligencia Artificial (Gemini) y se entrega a la comunidad como una contribución al conocimiento libre.

  Licencia: Este trabajo está dedicado al dominio público mediante la licencia CC0 1.0 Universal.

  Sin Derechos Reservados: Puedes copiar, modificar, distribuir y ejecutar el trabajo, incluso con fines comerciales, sin necesidad de permiso ni atribución.

🚀 Instalación y Uso

  Clona el repositorio:

  ''git clone [https://github.com/OrangyDev/bad-apple-kinetic.git](https://github.com/OrangyDev/bad-apple-kinetic.git''


Abre index.html en cualquier navegador moderno.

Haz clic en "COMENZAR EXPERIENCIA".

Contribución al dominio público.
