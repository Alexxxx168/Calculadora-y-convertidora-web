Calculadora & Convertidor Universal 

Una herramienta web moderna, modular y responsiva que combina una calculadora funcional con potentes convertidores de unidades (Peso y Distancia). Este proyecto fue diseñado con un enfoque en la modularización de JavaScript y una experiencia de usuario fluida.

Características
Calculadora Funcional: Soporta operaciones básicas, borrado parcial, limpieza total y uso de decimales.

Soporte de Teclado: Permite introducir números y realizar cálculos usando el teclado físico (Enter, Backspace, números y operadores).

Convertidor de Peso: Soporta Kilogramos, Libras, Toneladas, Gramos y Onzas.

Convertidor de Distancia: Soporta Metros, Kilómetros, Centímetros, Pulgadas, Pies, Yardas y Millas.

Diseño Responsivo: Interfaz adaptada para dispositivos móviles y escritorio con un estilo moderno tipo Glassmorphism.

Navegación Modular: Sistema de pestañas para cambiar entre herramientas sin recargar la página.

Tecnologías utilizadas
HTML5: Estructura semántica.

CSS3: Diseño personalizado, Grid Layout, Flexbox y animaciones.

JavaScript (ES6+): Implementación de módulos (import/export), manejo del DOM y lógica matemática.

Estructura del Proyecto
El código está organizado de forma modular para facilitar su mantenimiento:

Plaintext

├── index.html          # Estructura principal de lo que se verá en la web
├── css/
│   └── styles.css      # Estilos generales y del sistema de pestañas
└── js/
    ├── main.js         # Orquestador y gestión de navegación
    ├── calculadora.js  # Lógica de la calculadora y eventos de teclado
    ├── convertidordepeso.js    # Lógica y tasas de unidades de masa
    └── convertidordistancia.js # Lógica y tasas de unidades de longitud

-Instalación y Uso
Clona este repositorio o descarga los archivos.

Dado que el proyecto utiliza módulos de JavaScript, es necesario ejecutarlo a través de un servidor local para evitar errores de CORS

Si usas VS Code, te recomiendo la extensión Live Server.

Alternativamente, puedes usar Python con python -m http.server.

Abre index.html en tu navegador.

Próximas Mejoras
[ ] Añadir historial de cálculos en la calculadora.

[ ] Añadir más funciones a la calculadora.

[ ] Implementar un Modo Oscuro (Dark Mode).

[ ] Agregar convertidor de divisas con una API en tiempo real.

Desarrollado por Alex Baltodano - https://github.com/Alexxxx168?tab=repositories
