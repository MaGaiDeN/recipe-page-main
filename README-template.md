# Frontend Mentor - Recipe page solution

Esta es una solución para el [Recipe page challenge en Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Los desafíos de Frontend Mentor ayudan a mejorar las habilidades de codificación mediante la construcción de proyectos realistas.

## Tabla de contenidos

- [Resumen](#resumen)
  - [El desafío](#el-desafío)
  - [Capturas de pantalla](#capturas-de-pantalla)
  - [Enlaces](#enlaces)
- [Mi proceso](#mi-proceso)
  - [Construido con](#construido-con)
  - [Lo que aprendí](#lo-que-aprendí)
  - [Desarrollo continuo](#desarrollo-continuo)
  - [Recursos útiles](#recursos-útiles)
- [Autor](#autor)

## Resumen

### El desafío

Los usuarios deberían poder:

- Ver el layout óptimo dependiendo del tamaño de pantalla de su dispositivo
- Ver estados hover y focus para elementos interactivos

### Capturas de pantalla

![Vista Desktop](./screenshot-desktop.jpg)
![Vista Mobile](./screenshot-mobile.jpg)

### Enlaces

- URL de la solución: [Repositorio GitHub](https://github.com/tu-usuario/recipe-page)
- URL del sitio en vivo: [Ver página](https://tu-usuario.github.io/recipe-page)

## Mi proceso

### Construido con

- HTML5 semántico
- Propiedades personalizadas CSS
- Flexbox
- CSS Grid
- Flujo de trabajo Mobile-first
- Fuentes locales (Young Serif y Outfit)
- Metodología BEM para nombrado de clases

### Lo que aprendí

- Implementación de fuentes locales en un proyecto web
- Uso de CSS Grid para la sección de nutrición
- Manejo de responsive design con breakpoints específicos
- Estructuración semántica de una receta en HTML

```html
<!-- Ejemplo de estructura semántica para la sección de nutrición -->
<dl class="nutrition-list">
    <div class="nutrition-item">
        <dt>Calories</dt>
        <dd>277kcal</dd>
    </div>
</dl>
```

```css
/* Ejemplo de implementación de fuentes locales */
@font-face {
    font-family: 'Young Serif';
    src: url('./young-serif/YoungSerif-Regular.ttf') format('truetype');
    font-weight: 400;
}
```

### Desarrollo continuo

- Mejorar la accesibilidad del sitio
- Implementar animaciones suaves en las transiciones
- Optimizar el rendimiento de las imágenes
- Añadir más interactividad a la página

### Recursos útiles

- [CSS-Tricks Grid Guide](https://css-tricks.com/snippets/css/complete-guide-grid/) - Guía completa de CSS Grid
- [MDN Web Docs](https://developer.mozilla.org/es/) - Documentación detallada de HTML y CSS
- [Frontend Mentor](https://www.frontendmentor.io) - Desafíos para practicar

## Autor

- Website - [Carlos Sánchez](https://sientelared.com)
- Frontend Mentor - [@MaGaiDeN](https://www.frontendmentor.io/profile/MaGaiDeN)
- GitHub - [@MaGaiDeN](https://github.com/MaGaiDeN)
