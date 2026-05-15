# "Sociedad de Almas"
Proyecto intermodular que integra desarrollo de software, administración de sistemas y diseño web, con el objetivo de simular un entorno tecnológico real.

Incluye:
- Videojuego 2D en Java
- Sistema ERP/CRM orientado al sector veterinario
- Infraestructura cliente-servidor
- Landing Page profesional responsive

## Descripción del proyecto

Este proyecto demuestra competencias técnicas transversales en distintas áreas del desarrollo tecnológico.
Se ha diseñado como una simulación de un entorno profesional real, donde se combinan distintas soluciones digitales para cubrir necesidades específicas:

- Desarrollo de software interactivo
- Gestión empresarial mediante ERP/CRM
- Administración de sistemas y redes
- Diseño y desarrollo web

## Tecnologías utilizadas

### Desarrollo y programación
- **Java & Java Swing** → Desarrollo del videojuego 2D (lógica, eventos, interfaz gráfica)
- **HTML5, CSS3, JavaScript** → Desarrollo de la Landing Page (enfoque Mobile First)
  -HTML5: Estructuración y maquetación semántica del contenido web.
  -CSS: Diseño visual, definición de la paleta de colores corporativa, tipografías y adaptabilidad (Responsive Design).
  -JavaScript: Implementación de dinamismo e interactividad mediante la manipulación del DOM y gestión de eventos.
- **Markdown** → Documentación técnica y profesional del repositorio, garantizando una lectura clara y estructurada del proyecto.

### Gestión de datos
- **MySQL & MySQL Workbench** →  Diseño, administración y optimización de la base de datos Football Manager.
  -Triggers: Implementación de lógica automática para mantener la integridad de los datos.
  -Procedures: Encapsulamiento de consultas complejas para mejorar el rendimiento del servidor y centralizar la lógica de negocio.
- **JDBC** → Conexión entre Java y la base de datos por medio de mysql
   -Conectividad: Gestión de la conexión mediante el driver oficial para asegurar el intercambio de información.
   -Consultas Dinámicas: Uso de sentencias SQL desde el código para la gestión de altas, bajas y consultas en tiempo real.


### Sistemas y herramientas
- **Git & GitHub** → Control de versiones y gestión del proyecto
- **Ubuntu 22.04 , Windows Server 2019, Windows 10** → Administración de sistemas.
   -Configuración de Red: Implementación de entornos virtuales utilizando Red NAT para entornos aislados y Modo Puente (Bridge) para garantizar la visibilidad y conectividad real entre el cliente y el servidor.
   -Arquitectura Cliente-Servidor: Uso de Windows 10 como cliente para validar servicios alojados en servidores Ubuntu y Windows Server, asegurando una comunicación fluida mediante protocolos estándar.
- **UML** → Modelado de sistemas (casos de uso y diagramas)
- **Dolibarr** → Implementación y personalización de una solución empresarial para la gestión administrativa, cubriendo procesos de facturación, gestión de productos y servicios.

## Funcionalidades principales

- **Videojuego 2D interactivo**
  - Gestión de eventos de teclado
  - Renderizado de elementos gráficos
  - Interacción entre componentes

- **Base de datos automatizada**
  - Uso de triggers y procedures
  - Integridad y eficiencia de datos
  - Gestión de altas de usuarios y guardado de estadísticas de partida desde Java.

- **Landing Page responsive**
  - Diseño adaptable a móvil y escritorio
  - Estructura clara y profesional

- **Infraestructura cliente-servidor**
  - Conectividad entre sistemas Windows y Linux
  - Configuración de red funcional
 
## Mi contribución

Dentro del proyecto he sido responsable de:

- Desarrollo del videojuego 2D en Java (lógica y eventos) y su integración con MySQL mediante JDBC.
- Implementación de la interfaz gráfica con Java Swing
- Diseño y desarrollo de la Landing Page
- Configuración de servidores en Ubuntu y Windows Server
- Diseño y automatización de la base de datos en MySQL
- Resolución de problemas de conectividad en red
- Documentación completa del proyecto

## Problemas encontrados y soluciones aplicadas

Durante el desarrollo del proyecto surgieron diferentes problemas técnicos y de diseño en varias áreas. A continuación, se detallan junto con las soluciones implementadas:

### Diseño y manual de identidad corporativa

**Problemas:**
- Dificultad para seleccionar una paleta de colores adecuada.
- Problemas para combinar colores de forma visualmente atractiva.
- Dificultades en la maquetación y organización de la Landing Page.
- Problemas al estructurar la interfaz mediante wireframes.

**Soluciones:**
- Pruebas iterativas de combinaciones de colores hasta definir una identidad visual coherente.
- Análisis de referencias de diseño web (UX/UI).
- Reorganización de la estructura visual de la página.
- Uso de wireframes previos para planificar el diseño antes del desarrollo.

### Desarrollo en Java (Java Swing)

**Problemas:**
- Dificultades en la gestión de eventos.
- Problemas al implementar componentes gráficos:
 - JPanel
 - JLabel
 - JButton
- Complejidad en la organización de ventanas e interacción entre componentes.

**Soluciones:**
- Desarrollo de pruebas prácticas para comprender el funcionamiento de eventos.
- Separación de la lógica de negocio y la interfaz gráfica.
- Mejora de la organización del código para facilitar la escalabilidad.

### Sistemas y servidores

**Problemas:**
- Errores en la configuración de red en máquinas virtuales.
- Uso inconsistente de adaptadores de red (Host-Only vs Puente).
- Falta de conexión entre máquinas y servidores.
- Dificultades para verificar la comunicación cliente-servidor.

**Soluciones:**
- Revisión de la configuración de red con apoyo técnico.
- Uso definitivo del modo de red “Puente” para asegurar conectividad.
- Corrección de la configuración de red en todas las máquinas.
- Realización de pruebas de conectividad para validar la comunicación entre sistemas.

## Aprendizajes obtenidos

Este proyecto me ha permitido desarrollar competencias técnicas y profesionales clave:

- Desarrollo de aplicaciones en Java con Java Swing
- Diseño de interfaces web responsive (Mobile First)
- Administración básica de sistemas Linux y Windows Server
- Diseño y automatización de bases de datos con MySQL
- Uso de control de versiones con Git y GitHub
- Resolución de problemas en entornos reales
- Organización y documentación de proyectos técnicos

