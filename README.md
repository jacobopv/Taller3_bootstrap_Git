# 🏀 NBA Web Project - Taller 3: Bootstrap & Git

Este proyecto consiste en un sitio web dinámico, moderno e interactivo dedicado enteramente a la **NBA**, desarrollado como parte del proceso de formación en maquetación web. La propuesta estética implementa de manera estricta la paleta de colores oficial e identitaria de la liga: fondo oscuro (`bg-dark`), contenedores negros (`bg-black`), e hilos de realce en dorado brillante (`text-warning` / `border-warning`).

La interfaz ha sido diseñada bajo el estándar *Mobile-First*, lo que garantiza que sea **100% responsiva** y se adapte de forma fluida desde teléfonos móviles pequeños hasta pantallas de escritorio de gran resolución.

---

## 🛠️ Tecnologías y Librerías

El desarrollo se construyó utilizando tecnologías nativas de la web y frameworks de maquetación ágil:
* **HTML5 Semántico:** Organización estructurada y limpia de las etiquetas para una base sólida.
* **Bootstrap v5.3.8:** Uso avanzado del sistema de rejillas (*Grid System*), utilidades de espaciado (`me-`, `mb-`, `px-`), alineación y componentes interactivos integrados.
* **Bootstrap Icons v1.13.1:** Iconografía vectorial fluida para dotar de identidad visual a los botones, enlaces y títulos.

---

## 📂 Estructura del Sitio y Componentes

El proyecto se distribuye con una página de aterrizaje principal en la raíz y módulos específicos organizados dentro de la carpeta `/app`:

### 🏠 1. Inicio (`index.html`)
Es el eje central de la plataforma. Integra componentes dinámicos de experiencia de usuario:
* **Navbar Sticky:** Barra de navegación fija en la parte superior (`sticky-top`) con logotipo de la NBA, menú colapsable para móviles y un menú desplegable interactivo (*Dropdown*) para alternar limpiamente entre los subproyectos.
* **Carrusel Dinámico:** Deslizador de imágenes (`carousel slide`) con controles interactivos de navegación que destaca a superestrellas como Michael Jordan, LeBron James y Stephen Curry.
* **Acordeón Temático:** Estructura colapsable (`accordion-flush`) que desglosa cronológicamente momentos históricos de la liga de forma compacta y elegante.
* **Tarjetas y Grupos de Listas:** Uso de contenedores `card` y listas `list-group` con variantes oscuras para clasificar las conferencias Este/Oeste y los campeonatos de las franquicias más ganadoras.

### 📊 2. Tabla de Jugadores (`app/table.html`)
Módulo especializado en la visualización estructurada de datos de alta densidad:
* **Matriz Compleja:** Una tabla organizada que cruza y lista la información de 20 jugadores históricos distribuidos a través de las 10 franquicias más importantes del torneo.
* **Contenedor Adaptativo:** Envoltura con desplazamiento horizontal responsivo (`overflow-x: auto`), lo que previene que la enorme matriz rompa la cuadrícula o genere desbordamientos molestos en pantallas móviles.

### 💻 3. Guía de Git y GitHub (`app/git.html`)
Sección didáctica diseñada para documentar el proceso de control de versiones del proyecto:
* **Secuencia de Configuración:** Guía paso a paso en 7 bloques secuenciales, cubriendo desde la verificación de la versión local (`git --version`) hasta el despliegue final en la nube.
* **Simulación de Terminales:** Bloques de código (`<code>` dentro de contenedores oscuros) que aíslan visualmente los comandos simulando consolas reales del sistema.

### 🔐 4. Módulo de Acceso (`app/login.html`)
Interfaz limpia y simétrica pensada para la gestión simulada de cuentas:
* **Diseño Split en Bloques:** Uso de columnas responsivas (`col-md-6`) para maquetar de forma paralela un formulario completo de **Registro** y otro de **Inicio de Sesión** en una misma vista organizada.
* **Validación de Entradas:** Inputs optimizados con utilidades estéticas nativas para maximizar la usabilidad del usuario.

---

## 🚀 Instalación y Visualización Local

Si deseas descargar el proyecto para inspeccionar el código o previsualizarlo localmente, ejecuta la siguiente secuencia en tu terminal de comandos:

1. **Clonar el repositorio:**
   ```bash
   git clone [https://github.com/jacobopv/Taller3_bootstrap_Git.git](https://github.com/jacobopv/Taller3_bootstrap_Git.git)
