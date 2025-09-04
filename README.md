# Temario App Web

Copilot said: ````markdown ## Propósito de Aprendizaje 1: Comprender los
Markdown
## Propósito de Aprendizaje 1: Comprender los fundamentos del desarrollo de aplicaciones web
<img width="194" height="179" alt="image" src="https://github.com/user-attachments/assets/504cab27-df00-4689-b42e-df547e736494" />

El desarrollo web es el proceso de crear aplicaciones y sitios accesibles desde cualquier dispositivo con navegador. Comienza con la creación de páginas web simples y ha evolucionado hasta aplicaciones complejas y dinámicas.

**Historia y evolución del desarrollo web**  
- **Década de 1990:** La web comenzó como un conjunto de páginas estáticas escritas en HTML, accesibles mediante navegadores básicos.
- **2000 en adelante:** Aparecen tecnologías como CSS y JavaScript, permitiendo páginas más ricas y dinámicas. Surgen los primeros CMS y el auge del comercio electrónico.
- **Actualidad:** Predominan las aplicaciones interactivas, con arquitecturas avanzadas y experiencias similares a las de aplicaciones nativas.

**Tipos de aplicaciones web**  
- **Estáticas:** Su contenido no cambia, se entrega tal cual está en el servidor (ej: una landing page básica).
- **Dinámicas:** El contenido puede variar según el usuario o la interacción (ej: redes sociales, foros).
- **SPA (Single Page Application):** Aplicaciones de una sola página que cargan dinámicamente el contenido sin recargar toda la página (ej: Gmail, Trello).
- **PWA (Progressive Web App):** Aplicaciones web que funcionan como apps nativas, con características como trabajo offline y notificaciones push.

---

### 2. Arquitectura de aplicaciones web

El desarrollo de aplicaciones web modernas requiere comprender las diferentes arquitecturas que permiten su funcionamiento eficiente, seguro y escalable.

**Cliente-Servidor**  
- El cliente (navegador) solicita recursos y servicios al servidor.
- El servidor procesa la solicitud, accede a datos y responde con la información solicitada.

**Arquitectura de tres capas**  
- **Presentación:** Interfaz con la que interactúa el usuario, usualmente creada con HTML, CSS y JavaScript.
- **Lógica de negocio:** Procesa datos y reglas del negocio, implementada en el backend.
- **Datos:** Almacenamiento y recuperación de la información, normalmente en bases de datos.

**REST y API-first design**  
- **REST:** Un estilo arquitectónico para diseñar servicios web que usan HTTP para comunicarse. Facilita la integración entre diferentes sistemas.
- **API-first design:** Enfoque que prioriza el diseño y desarrollo de APIs antes que la implementación de interfaces, permitiendo flexibilidad y escalabilidad.

---

### 3. Lenguajes y tecnologías fundamentales

El desarrollo web se apoya en un conjunto de lenguajes y tecnologías esenciales:

- **HTML (HyperText Markup Language):** Estructura básica de las páginas web.
- **CSS (Cascading Style Sheets):** Define estilos y presentación visual.
- **JavaScript:** Añade interactividad y dinamismo en el lado del cliente.
- **PHP:** Lenguaje de programación muy utilizado en el backend para crear aplicaciones dinámicas.
- **MySQL:** Sistema de gestión de bases de datos relacional, utilizado para almacenar y recuperar información.

---

### 4. Control de versiones

El control de versiones es fundamental para gestionar el desarrollo colaborativo y la evolución del código fuente.

- **Git:** Sistema de control de versiones distribuido que permite registrar cambios, colaborar y mantener un historial del proyecto.
- **GitHub:** Plataforma basada en Git para alojar repositorios y facilitar la colaboración entre desarrolladores.

**Flujo de trabajo con ramas (branching, merge, pull requests):**
- **Branching:** Crear ramas para desarrollar nuevas características o solucionar errores sin afectar la rama principal.
- **Merge:** Unir cambios realizados en diferentes ramas.
- **Pull Requests:** Proceso para revisar y fusionar cambios en el código, promoviendo la colabor Propósito de Aprendizaje 1: Comprender los fundamentos del desarrollo de aplicaciones web

## Propósito de Aprendizaje 2: Desarrollar componentes y funcionalidades de una aplicación web
<img width="238" height="160" alt="image" src="https://github.com/user-attachments/assets/88376cd3-6ead-4d33-9469-6c312d3b7301" />


A continuación se describen los elementos fundamentales para desarrollar los distintos componentes y funcionalidades que conforman una aplicación web moderna:

---

### 1. Diseño e implementación del frontend

- **Maquetación/Wireframe/Mockup:**  
  Es el proceso de planificar y diseñar la estructura visual de la aplicación.  
  - *Wireframe:* Bocetos básicos que muestran la disposición de los elementos en la interfaz.
  - *Mockup:* Prototipos más detallados y visuales que representan mejor el diseño final.
  - *Maquetación:* Traducción de estos prototipos a código (HTML/CSS), creando la estructura y estilos del frontend.

- **API:**  
  El frontend se comunica con el backend a través de APIs (Interfaz de Programación de Aplicaciones), generalmente utilizando HTTP.  
  Estas APIs permiten al frontend solicitar, enviar y actualizar datos de manera dinámica, haciendo la aplicación interactiva y conectada con el servidor.

---

### 2. Diseño e implementación del backend

- **Servidor:**  
  Es la aplicación que recibe y procesa las peticiones del cliente (frontend). Se encarga de gestionar la lógica de negocio, autenticar usuarios, y servir los datos necesarios.

- **Manejo de peticiones y respuestas HTTP:**  
  El backend debe ser capaz de recibir peticiones HTTP (GET, POST, PUT, DELETE, etc.), procesarlas y devolver respuestas adecuadas en formato JSON, HTML u otros.

- **Conexión a bases de datos (MySQL, PostgreSQL, MongoDB):**  
  El backend interactúa con sistemas de bases de datos para almacenar, recuperar, actualizar y eliminar información persistente según las solicitudes de la aplicación.

---

### 3. Bases de datos

- **Modelado de datos y relaciones:**  
  Es el proceso de diseñar cómo se organizarán y relacionarán los datos dentro de la base de datos (tablas, campos, claves foráneas, etc.), asegurando integridad y eficiencia.

- **ORM (Object Relational Mapping):**  
  Es una técnica que permite interactuar con la base de datos utilizando objetos del lenguaje de programación en lugar de escribir consultas SQL directamente. Ejemplos de ORMs: SQLAlchemy (Python), Sequelize (Node.js), Eloquent (Laravel).

- **CRUD desde el backend:**  
  El backend debe implementar operaciones básicas sobre los datos:  
  - *Crear (Create)*
  - *Leer (Read)*
  - *Actualizar (Update)*
  - *Eliminar (Delete)*
  Estas acciones son fundamentales para cualquier aplicación web funcional.

---

### 4. Seguridad básica en aplicaciones web

- **Validación de formularios:**  
  Consiste en verificar que los datos ingresados por el usuario cumplen con los requisitos esperados antes de procesarlos o almacenarlos, previniendo errores y posibles ataques.

- **Autenticación y autorización:**  
  - *Autenticación:* Verifica la identidad de los usuarios (por ejemplo, mediante usuario y contraseña).
  - *Autorización:* Determina los permisos de acceso que tiene un usuario una vez autenticado, restringiendo o permitiendo el acceso a ciertas funcionalidades o datos según el rol.

---
## Propósito de Aprendizaje 3: Implementar y desplegar una aplicación web funcional
<img width="295" height="161" alt="image" src="https://github.com/user-attachments/assets/6ad7b860-cb81-4853-b3c9-9b1e12d957b5" />


A continuación se describe cada uno de los elementos clave para lograr una aplicación web completa, lista para ser utilizada por los usuarios finales:

---

### 1. Integración de frontend y backend

**Interfaz de usuario Frontend:**  
Es la parte visual e interactiva de la aplicación web con la que los usuarios se relacionan directamente. Aquí se implementan los diseños, estilos, y la lógica de interacción usando tecnologías como HTML, CSS y JavaScript (o frameworks modernos como React, Vue o Angular). El frontend debe ofrecer una experiencia intuitiva, rápida y adaptada a diferentes dispositivos.

**Manejo de API:**  
La integración entre el frontend y el backend se logra a través de APIs (Interfaz de Programación de Aplicaciones). El frontend envía solicitudes a la API para obtener o enviar datos, y la API responde con la información necesaria en formatos como JSON o XML. Esta comunicación permite que la interfaz de usuario sea dinámica y que los datos estén siempre actualizados.

**Proceso de Solicitud y Respuesta de Backend:**  
El backend es el encargado de recibir las solicitudes del frontend, procesarlas —aplicando la lógica de negocio—, interactuar con la base de datos si es necesario, y devolver una respuesta adecuada. Este proceso incluye:
- Validar datos recibidos.
- Consultar o modificar información en la base de datos.
- Generar respuestas estructuradas (normalmente en JSON) para el frontend.

---


# temario-app-web
