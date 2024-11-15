# Proyecto Final del Módulo de CSS

## Descripción
El objetivo de este proyecto es desarrollar una página web estilizada que demuestre conocimientos avanzados de CSS. Se aplicarán técnicas como diseño responsive, Flexbox, modelo de caja, y buenas prácticas de arquitectura CSS.

## Live Preview
![Captura pagina inicial](/docs/cook-eccomerce-website.png) 

Mi resultado: [Live Preview](https://eltiempo-project.netlify.app)

Pongo un enlace a la web orginal, aun que no la consulte para realizar este ejercicio. Lo unico que tuvve para llegar a este resultado fue una captura de pantalla de la web completa, a partir de la cual tuve que plantear toda la web.

Fuente original: [Enlace a web original](https://web.archive.org/web/20240720005816/https://www.eltiempo.es/)



## Tecnologías Usadas
- **HTML5** - Estructura semántica del proyecto.
- **CSS3 (Flexbox, Grid)** - Diseño adaptable y manejo de contenedores.
- **SASS (opcional)** - Preprocesador CSS para optimización del código.
- **Google Fonts** - Tipografía personalizada.
- **CSS Variables** - Uso de variables para un diseño consistente y escalable.

## Buenas Prácticas Aplicadas
- **Mobile First**: Diseño inicial optimizado para dispositivos móviles y adaptado a pantallas más grandes.
- **Arquitectura CSS con BEM**: Organización de clases CSS eficiente y escalable.
- **Código reutilizable y limpio**: Uso de variables, mixins (si aplica SASS), y código bien estructurado.
- **Uso combinado de Flexbox y Grid**: Implementación estratégica para crear un diseño más versátil.
- **Colores accesibles**: Paleta con buen contraste para garantizar una experiencia accesible para todos los usuarios.

## Detalles del Proyecto
Este proyecto incluye los siguientes componentes clave:

### Requisitos Específicos
1. **Idea y Planteamiento**:
   - Establecer las funcionalidades principales pensando en el usuario.
   - Prototipo inicial en papel o digital, definiendo la estructura principal (Nav, Header, Main, Footer).

2. **Estructura HTML**:
   - Organización semántica clara y compatible con los estilos de CSS.

3. **Modelo de Caja (Box Model)**:
   - Aplicación de propiedades como `padding`, `margin` y `width` para diseño limpio.

4. **Flexbox**:
   - Uso en al menos dos secciones (barra de navegación, galería de imágenes, etc.).

5. **Responsive Design**:
   - Diseño adaptable a diferentes tamaños de pantalla con media queries (`@media`).

6. **Barra de Navegación**:
   - Menú adaptable con diseño de hamburguesa para pantallas pequeñas.

7. **Formulario Estilizado**:
   - Creación de un formulario con estilos personalizados y efectos interactivos (`:hover`, `:focus`).

8. **Imágenes Responsivas**:
   - Imágenes adaptadas con `width: 100%` y uso opcional del atributo `srcset`.

### Requisitos Avanzados (Nivel Samurai)
- **Metodología Mobile First**: Diseño que crece desde pantallas móviles hacia dispositivos más grandes.
- **Flexbox y Grid en Combinación**: Uso de CSS Grid para cuadrículas y Flexbox para posicionamiento.
- **Variables CSS**: Definición de colores, fuentes y valores reutilizables.
- **SASS** (Opcional): Uso de preprocesador CSS para optimizar el desarrollo.

### Retos y Soluciones
- **Reto 1**: Diseñar una estructura completamente responsive.
  - **Solución**: Utilizar media queries de forma estratégica, asegurando escalabilidad en cada sección.
  
- **Reto 2**: Combinar Flexbox y Grid en un solo proyecto.
  - **Solución**: Implementar Flexbox para posicionamiento en secciones pequeñas y Grid para cuadrículas en áreas más complejas.

- **Reto 3**: Uso de BEM para mantener un CSS limpio.
  - **Solución**: Nombrar las clases siguiendo la estructura `bloque__elemento--modificador`.

---

_Este documento ha sido creado como parte de mi máster en programación._

