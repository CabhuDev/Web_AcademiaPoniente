# Academia Poniente - Landing Page y Canal RSS

Este proyecto consiste en una **landing page** desarrollada para la "Academia de Formación Poniente", con el objetivo de mejorar su presencia en Internet y atraer nuevas matrículas. Además, se incluye un canal de sindicación **RSS 2.0** que proporciona información actualizada de la academia.

## Estructura del Proyecto

```
/img              # Carpeta que contiene las imágenes utilizadas en el sitio web.
  logo.png        # Logotipo de la academia.
  banner.jpg      # Imagen principal de la landing page.
  science.png     # Imagen de servicios de ciencias.
  language.png    # Imagen de servicios de idiomas.
  maths.png       # Imagen de matemáticas.
  apoyo.jpeg      # Imagen de clases de apoyo.

/css              # Carpeta que contiene los estilos CSS.
  style.css       # Archivo de estilos de la landing page.

/feed             # Carpeta que contiene el archivo RSS.
  canal.rss       # Canal de sindicación RSS 2.0.

/index.html       # Página principal de la landing page.
```

## Funcionalidades del Proyecto

### Landing Page
- **Encabezado**:
  - Menú de navegación con enlaces a Inicio, Servicios y Contacto.
  - Logotipo de la academia.
  
- **Inicio**:
  - Banner de bienvenida.
  - Párrafo introductorio y lista de servicios organizados jerárquicamente.

- **Servicios**:
  - Galería de imágenes con información sobre los servicios ofrecidos.
  - Efectos visuales al pasar el ratón sobre las imágenes (configurable en CSS).

- **Contacto**:
  - Formulario de contacto con campos como nombre, email, teléfono, ciudad y comentarios.
  - Opción para elegir el medio de respuesta (email o teléfono).

- **Pie de Página**:
  - Información de contacto de la academia.
  - Enlace al canal RSS.

### Canal RSS
- Implementado en formato **RSS 2.0**.
- Contiene:
  - Información del canal (nombre, descripción, idioma, categorías, email del editor, etc.).
  - Dos entradas:
    - Noticia inventada sobre una startup andaluza.
    - Noticia basada en el impacto de la inteligencia artificial en la ciencia, extraída del CSIC.

## Validaciones
- **HTML**: Validado con el [W3C Markup Validation Service](https://validator.w3.org/).
- **CSS**: Validado con el [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/).
- **RSS**: Validado con el [W3C Feed Validation Service](https://validator.w3.org/feed/).

## Cómo Usar
1. Clona el repositorio:
   ```bash
   git clone https://github.com/CabhuDev/StaticWeb_AcademiaPoniente.git
   ```
2. Abre el archivo `index.html` en tu navegador para visualizar la página web.
3. Accede al archivo RSS ubicado en `/feed/canal.rss` para explorar el canal de sindicación.

## Tecnologías Utilizadas
- **HTML5**: Estructura del sitio web.
- **CSS3**: Estilos y diseño.
- **RSS 2.0**: Sindicación de contenidos.
- **Editor de texto**: Visual Studio Code.

## Autor
Desarrollado por **Pablo Cabello Hurtado** 

## Capturas de Pantalla
### Landing Page
![Landing Page](img/banner.jpg)

### Validaciones
- **HTML y CSS**:
  - Capturas de las validaciones realizadas con los servicios W3C.
- **RSS**:
  - Captura de la validación del archivo RSS con el W3C Feed Validation Service.


