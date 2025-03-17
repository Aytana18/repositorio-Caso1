# martur.io - Plataforma de Comunicación con Clientes

## Descripción del Proyecto

**martur.io** es una plataforma de comunicación diseñada para ayudar a las empresas a interactuar con sus clientes de manera eficiente. Ofrece herramientas como chat en vivo, gestión de tickets, base de conocimientos y seguimiento de actividad en tiempo real. La plataforma está diseñada para ser fácil de usar, escalable y completamente gratuita, con opciones premium para necesidades más avanzadas.

👉 **Ver la página en vivo**: [https://aytana18.github.io/repositorio-Caso1/](https://aytana18.github.io/repositorio-Caso1/)

---

## Características Principales

- **Chat en vivo**: Interactúa con tus clientes en tiempo real.
- **Gestión de tickets**: Organiza y responde a las solicitudes de soporte.
- **Base de conocimientos**: Proporciona a tus clientes recursos para resolver problemas por sí mismos.
- **Seguimiento en tiempo real**: Monitorea la actividad de los visitantes en tu sitio web.
- **Colaboración entre agentes**: Asigna conversaciones y colabora con tu equipo.
- **Integración con múltiples herramientas**: Soporta más de 45 idiomas y ofrece una API de JavaScript para integraciones personalizadas.

---

## Procedimientos Realizados

### 1. **Estructura del Proyecto**
   - **HTML5**: Se utilizó HTML5 para estructurar el contenido de la página, asegurando una semántica correcta y accesibilidad.
   - **Bootstrap 5**: Se implementó Bootstrap para el diseño responsive y componentes predefinidos como navegación, botones y tarjetas.
   - **Animate.css**: Se integró Animate.css para agregar animaciones sutiles a los elementos de la página, mejorando la experiencia del usuario.

### 2. **Diseño y Estilos**
   - **CSS Personalizado**: Se creó un archivo `styles.css` para personalizar los estilos y ajustar el diseño según las necesidades del proyecto.
   - **Bootstrap Icons**: Se utilizaron íconos de Bootstrap para mejorar la interfaz visual y proporcionar una experiencia más intuitiva.

### 3. **Funcionalidades**
   - **Animaciones**: Se agregaron animaciones como `animate-fade-in` y `animate-slide-in` para mejorar la interactividad.
   - **FAQ Colapsable**: Se implementó un sistema de preguntas frecuentes (FAQ) con secciones colapsables utilizando Bootstrap.
   - **Testimonios**: Se incluyó una sección de testimonios con tarjetas que muestran comentarios de usuarios satisfechos.

### 4. **Integración de Imágenes y Recursos**
   - **Imágenes**: Se utilizaron imágenes como `Diseño-sin-titulo-2.png`, `dashboard.png`, y `customers-world.png` para ilustrar las funcionalidades de la plataforma.
   - **Logos de Empresas**: Se incluyeron logos de empresas que confían en **martur.io** para respaldar la credibilidad del servicio.

### 5. **Footer y Legal**
   - **Footer**: Se diseñó un footer con enlaces rápidos, información de contacto y detalles legales.
   - **Derechos de Autor**: Se incluyó una sección de derechos de autor y marcas registradas.

---

## Herramientas Utilizadas

- **Bootstrap 5**: Para el diseño responsive y componentes UI.
- **Animate.css**: Para animaciones CSS.
- **Bootstrap Icons**: Para íconos visuales.
- **JavaScript**: Para funcionalidades dinámicas como el colapso de secciones FAQ.
- **HTML5 y CSS3**: Para la estructura y estilos del sitio.

---

## Capturas de Pantalla

A continuación, se muestra una captura de pantalla de la página principal de **martur.io**:

![image](https://github.com/user-attachments/assets/3408afff-27ce-49cc-8249-c80640f1b9eb)


---

## Instalación y Uso

### **Clonar el repositorio**

Clonar un repositorio es un proceso fundamental en el desarrollo de software, especialmente cuando trabajas con Git y GitHub. Te permite obtener una copia local de un proyecto alojado en un repositorio remoto (como GitHub), para que puedas trabajar en él, realizar cambios y contribuir.

#### **Pasos para clonar el repositorio:**

1. **Obtén la URL del repositorio**:
   - Ve al repositorio en GitHub (por ejemplo, `https://github.com/aytana18/repositorio-Caso1`).
   - Haz clic en el botón verde "Code" y copia la URL del repositorio. Puedes usar HTTPS o SSH, dependiendo de tu configuración.

2. **Abre tu terminal o línea de comandos**:
   - En Windows: Usa Git Bash, CMD o PowerShell.
   - En macOS o Linux: Usa la Terminal.

3. **Navega a la carpeta donde quieres clonar el repositorio**:
   - Usa el comando `cd` para moverte a la carpeta deseada. Por ejemplo:
     ```bash
     cd Documents/Proyectos
     ```

4. **Clona el repositorio**:
   - Usa el comando `git clone` seguido de la URL del repositorio. Por ejemplo:
     ```bash
     git clone https://github.com/aytana18/repositorio-Caso1.git
     ```
   - Esto creará una carpeta llamada `repositorio-Caso1` en tu directorio actual con todos los archivos del proyecto.

5. **Accede a la carpeta del proyecto**:
   - Usa el comando `cd` para entrar a la carpeta del proyecto:
     ```bash
     cd repositorio-Caso1
     ```

6. **Abre el proyecto en tu editor de código**:
   - Por ejemplo, si usas Visual Studio Code, puedes abrir el proyecto con:
     ```bash
     code .
     ```

---

### **Trabajar con el repositorio clonado**

#### **1. Realiza cambios**
   - Puedes abrir los archivos en tu editor de código (como Visual Studio Code, Sublime Text, etc.) y realizar modificaciones.

#### **2. Guarda tus cambios con Git**
   - Después de hacer cambios, usa los siguientes comandos para guardarlos:
     ```bash
     git add .
     git commit -m "Descripción de los cambios realizados"
     ```

#### **3. Sube tus cambios al repositorio remoto**
   - Si tienes permisos de escritura en el repositorio, puedes subir tus cambios con:
     ```bash
     git push origin main
     ```
   - Si no tienes permisos, puedes hacer un fork del repositorio y luego enviar un Pull Request.

---

### **Consejos adicionales**

1. **Usa ramas**: Si planeas hacer cambios importantes, crea una nueva rama con:
   ```bash
   git checkout -b nombre-de-la-rama
