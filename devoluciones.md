### Idea y diseño

- Bien el trabajo de diseño, ordenado y prolijo.
- La implementación tiene sus problemas, especialmente a la hora de armar los collages. Esos deberían estar armados con CSS.

### Generales

- No hace falta la carpeta FINAL HIPERMEDIAL ORGIA, mejor poner los archivos directamente en la carpeta raíz
- Es una mala práctica incluir el collage en una única imagen (a menos que sea un collage propiamente dicho),
  1. Dificulta la accesibilidad y el SEO. Mejor dividir en imágenes individuales con sus respectivos alt.
  2. Afecta la mantenibilidad del código, ya que si se quiere cambiar una imagen hay que editar el collage completo.
  3. El contenido queda acoplado a este diseño específico, perdiendo flexibilidad.
  4. Poca flexibilidad para el responsive.
  5. Texto pixelado, imposible de seleccionar no responde a preferencias del usuario. Afecta accesibilidad y SEO.
  6. Un cambio de texto implica re-editar la imagen.
  7. Un ajuste de padding implica re-editar la imagen.

### CSS

- Bien el uso de BEM, rem
- Aplica tamaños fluidos y media-queries. Ojo que había media-queries repetidos e incluso anidados. 

### HTML

- Simple, pero bien en general.
- Había etiquetas sin cerrar, que validando el código o formateandolo adecuadamente hubieran sido más notorias.
- El title debería ser único para cada página.
- Evitar uso de mayúsculas.
- Se exagera un poco con la división en section, hay una continuidad en el contenido y cada section tiene pocos elementos. Mejor usar div en estos casos.

### Astro y/o JS

No tiene

