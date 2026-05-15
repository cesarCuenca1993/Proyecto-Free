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
- **Java & Java Swing** → Utilizados para el desarrollo íntegro de la lógica del videojuego, la gestión de eventos de usuario y la creación de la interfaz gráfica de escritorio.
- **HTML5, CSS, JavaScript** → Empleados para la creación de la Landing Page con enfoque Mobile First.
  - HTML5: Estructuración y maquetación semántica del contenido web.
  - CSS: Para el diseño visual, definición de la identidad corporativa (colores y tipografía) y asegurar la adaptabilidad (Responsive Design).
  - JavaScript: Implementación de dinamismo e interactividad mediante la manipulación del DOM y gestión de eventos.
- **Markdown** → Documentación técnica y profesional del repositorio, garantizando una lectura clara y estructurada del proyecto.

### Gestión de datos
- **MySQL & MySQL Workbench** →  Diseño, administración y optimización de la base de datos Football Manager.
  - Triggers: Para automatizar la integridad de los datos de forma interna.
  - Procedures: Encapsulamiento de consultas complejas para mejorar el rendimiento del servidor.
- **JDBC** →Actúa como el puente de conexión crítico entre la lógica de Java y la base de datos MySQL, permitiendo realizar consultas dinámicas (altas y bajas) en tiempo real.


### Sistemas y herramientas
- **Git & GitHub** → Empleados para el control de versiones y la gestión organizada del historial del proyecto.
- **Ubuntu 22.04 , Windows Server 2019, Windows 10** → Utilizados para la administración de sistemas y simulación de un entorno cliente-servidor real
   - Configuración de Red: Uso de Red NAT para aislamiento y Modo Puente (Bridge) para permitir conectividad real entre las máquinas virtuales.
   - Arquitectura Cliente-Servidor: Uso de Windows 10 como cliente para validar servicios alojados en servidores Ubuntu y Windows Server, asegurando una comunicación fluida mediante protocolos estándar.
- **UML** → Modelado de sistemas (casos de uso y diagramas)
- **Dolibarr** → Implementación y personalización de una solución empresarial para la gestión administrativa, cubriendo procesos de facturación, gestión de productos y servicios.

## Funcionalidades principales

- **Videojuego 2D interactivo**
  - Implementación de gestión de eventos de teclado, mouse en tiempo real para el movimiento y acciones del personaje.
  - Renderizado eficiente de elementos gráficos y gestión de colisiones entre componentes.
  - Menús interactivos y paneles de juego desarrollados con Java Swing.

- **Base de datos automatizada**
  - Gestión de altas de nuevos usuarios y guardado automático de estadísticas de partida directamente desde la aplicación Java mediante JDBC.
  - Uso de Triggers y Stored Procedures para automatizar procesos internos, garantizando la integridad y eficiencia de los datos.

- **Landing Page responsive**
  - Diseño optimizado para una visualización perfecta tanto en dispositivos móviles como en ordenadores de escritorio.
  - Estructura clara y profesional orientada a la presentación del producto y la identidad corporativa.

- **Infraestructura cliente-servidor**
  - Conectividad robusta entre sistemas operativos heterogéneos (Windows 10 como cliente y servidores Linux/Windows).
  - Configuración de adaptadores de red que permiten la comunicación real entre máquinas virtuales, simulando un entorno de producción empresarial.
 
## Mi contribución

Dentro del proyecto he sido responsable de:

- Programación completa de la lógica del videojuego 2D, incluyendo la implementación de la capa de persistencia mediante JDBC para la comunicación con MySQL.
- Creación y maquetación de todas las ventanas y componentes visuales utilizando Java Swing, asegurando una experiencia de usuario fluida.
- Diseño y programación desde cero de la Landing Page, aplicandoel manual de identidad corporativa
- Configuración de servidores en Ubuntu , Windows Server y Windows 10 gestionando la seguridad, red y los servicios.
- Resolución de incidencias críticas de conectividad en entornos virtuales, garantizando la comunicación estable en la arquitectura cliente-servidor.
- Redacción de la documentación técnica completa, manuales de identidad y guías de configuración del proyecto.

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

- Desarrollo de aplicación en Java con Java Swing y con conectividad JDBC para gestión de datos.
- Dominio de la metodología Mobile First, logrando interfaces adaptables (responsive) y optimizadas para cualquier dispositivo.
- Administración de servidores Linux/Windows, cogestionando infraestructuras de red y asegurando la comunicación mediante protocolos HTTP/HTTPS.
- Diseño y automatización de bases de datos con MySQL
- Uso fluido de Git y GitHub como herramientas esenciales para la trazabilidad del código y la gestión profesional del proyecto.
- Mejora en la capacidad de diagnóstico y solución de problemas técnicos complejos en entornos cliente-servidor y redes virtuales.
- Organización y documentación de proyectos técnicos
## Video
https://www.loom.com/share/38dc57a38e4147f4ac78bd2ead3393cb
