# 📝 Taller: Introducción a HTML y CSS

---

## 1. ¿Qué es HTML y cuál es su función en la web?
**R/**  
HTML (Lenguaje de Marcas de Hipertexto, del inglés HyperText Markup Language) es el componente más básico de la Web. Define el significado y la estructura del contenido web. Además de HTML, generalmente se utilizan otras tecnologías para describir la apariencia/presentación de una página web (CSS) o la funcionalidad/comportamiento (JavaScript).

"Hipertexto" hace referencia a los enlaces que conectan páginas web entre sí, ya sea dentro de un único sitio web o entre sitios web. Los enlaces son un aspecto fundamental de la Web. Al subir contenido a Internet y vincularlo a las páginas creadas por otras personas, te conviertes en un participante activo en la «World Wide Web» (Red Informática Mundial).

---

## 2. ¿Qué es una etiqueta HTML y menciona las etiquetas más comunes?
**R/**  
Una etiqueta en HTML es un fragmento de código que define un elemento en un documento web, proporcionando instrucciones al navegador sobre cómo debe mostrar el contenido.  
Estas etiquetas se encierran entre corchetes angulares `<` y `>` y su nombre no distingue entre mayúsculas y minúsculas.

Las etiquetas HTML más comunes son fundamentales para estructurar y presentar contenido en la web. Entre las más utilizadas se encuentran las etiquetas de apertura y cierre como `<html>`, `<head>`, `<body>`, que definen la raíz del documento y sus secciones principales.  
Las etiquetas `<title>` y `<meta>` son esenciales para el SEO y la gestión de metadatos del documento.  
Para estructurar el contenido, se utilizan frecuentemente `<h1>` a `<h6>` para encabezados, `<p>` para párrafos, `<div>` y `<span>` como contenedores genéricos, y `<a>` para crear hipervínculos.  
Además, las etiquetas `<img>`, `<iframe>`, `<video>`, y `<audio>` son clave para incrustar contenido multimedia.  
Las etiquetas `<ul>`, `<ol>`, `<li>`, `<dl>`, `<dt>`, y `<dd>` se emplean para crear listas, mientras que `<table>`, `<tr>`, `<td>`, y `<th>` son fundamentales para tablas.  
Finalmente, las etiquetas `<link>` y `<style>` permiten vincular hojas de estilo y definir estilos en línea, respectivamente.

---

## 3. ¿Qué es un atributo de una etiqueta HTML y menciona los más comunes?
**R/**  
Un atributo en una etiqueta HTML es una propiedad que proporciona información adicional al elemento.  

**Los más comunes son:**
- `id`: identificador único del elemento.  
- `class`: clase para estilos o scripts (puede repetirse).  
- `style`: define estilos CSS directamente.  
- `href`: enlace en etiquetas `<a>`.  
- `src`: ruta de imágenes o recursos.  
- `alt`: texto alternativo para imágenes.  
- `title`: información adicional que aparece al pasar el ratón.  

---

## 4. ¿Qué es CSS y cómo se utiliza para el diseño web?
**R/**  
CSS (Cascading Style Sheets) es un lenguaje que define el estilo y diseño de páginas web escritas en HTML. Permite controlar colores, fuentes, tamaños, márgenes, diseños y animaciones, separando el contenido visual de la estructura del documento.  

Se aplica mediante reglas que seleccionan elementos HTML y les asignan propiedades, como `color: blue;`.  

Los estilos pueden incluirse en archivos externos (`.css`), lo que facilita mantener un diseño consistente en múltiples páginas.  

CSS es esencial para crear sitios atractivos y responsivos.

---

## 5. ¿Qué es una propiedad en CSS y menciona las propiedades más comunes?
**R/**  
En CSS, una propiedad es una característica que se puede definir para un elemento HTML, como color, tamaño, posición, etc. Cada propiedad toma un valor que determina cómo se aplica el estilo.

### Propiedades comunes en CSS:
- **color:** Define el color del texto.  
  Ejemplo: `color: red;`

- **background-color:** Establece el color de fondo.  
  Ejemplo: `background-color: #f0f0f0;`

- **font-size:** Controla el tamaño del texto.  
  Ejemplo: `font-size: 16px;`

- **font-family:** Especifica la fuente del texto.  
  Ejemplo: `font-family: Arial, sans-serif;`

- **margin:** Define el margen externo de un elemento.  
  Ejemplo: `margin: 10px;`

- **padding:** Establece el espacio interno dentro del elemento.  
  Ejemplo: `padding: 20px;`

- **border:** Configura el borde del elemento (grosor, estilo y color).  
  Ejemplo: `border: 1px solid black;`

- **width** y **height:** Determinan el ancho y alto del elemento.  
  Ejemplo: `width: 200px;`

- **display:** Controla cómo se muestra el elemento (bloque, en línea, flex, grid, etc.).  
  Ejemplo: `display: flex;`

- **text-align:** Alinea el texto (izquierda, derecha, centro).  
  Ejemplo: `text-align: center;`

- **position:** Define el tipo de posicionamiento (static, relative, absolute, fixed).  
  Ejemplo: `position: relative;`

## 6. ¿Qué es un selector en CSS y cuáles tipos existen?
Un **selector** en CSS es la forma de indicar a qué elementos HTML se aplicarán los estilos.  
**Tipos principales:**
- **Universal (`*`)**: selecciona todos los elementos.  
- **De tipo (`p`, `div`)**: selecciona por nombre de etiqueta.  
- **De clase (`.clase`)**: selecciona por atributo `class`.  
- **De ID (`#id`)**: selecciona por atributo `id`.  
- **De atributo (`[attr]`)**: selecciona según atributos.  
- **Combinadores (`div p`, `div > p`)**: selecciona en relación jerárquica.  
- **Pseudoclases (`:hover`) y pseudoelementos (`::before`)**.  

---

## 7. ¿Qué es JavaScript y cómo añade la interactividad a las páginas web?
**JavaScript** es un lenguaje de programación que se ejecuta en el navegador.  
Permite **manipular el DOM**, responder a **eventos del usuario** (clics, teclas, etc.) y actualizar el contenido sin recargar la página, logrando interactividad dinámica.  

---

## 8. ¿Cuáles son los tipos de datos primitivos en JavaScript?
- **String**: texto (`"Hola"`)  
- **Number**: números (`10`, `3.5`)  
- **Boolean**: verdadero o falso (`true`, `false`)  
- **Null**: ausencia de valor intencional  
- **Undefined**: valor no asignado  
- **BigInt**: números muy grandes  
- **Symbol**: identificadores únicos  

---

## 9. ¿Cómo funcionan las estructuras de control de flujo en JavaScript?
- **if / else**: ejecutan bloques según condición.  
- **switch**: evalúa múltiples casos posibles.  
- **for / while / do-while**: repiten código hasta cumplir una condición.  
Se usan para controlar la **lógica y decisiones** en el programa.  

---

## 10. ¿Por qué es importante usar nombres significativos para variables y métodos?
Porque hace que el código sea:  
- **Más legible y entendible** para otros desarrolladores.  
- **Más fácil de mantener** y depurar.  
- Reduce **errores** al recordar su propósito.  

---

## 11. ¿Qué es una variable de entorno y por qué son importantes?
Son valores configurados fuera del código (ejemplo: claves, rutas, puertos).  
Importancia:  
- Permiten **configurar sin modificar el código**.  
- Aumentan la **seguridad** al no exponer información sensible.  
- Hacen el software **más portable** entre entornos (dev, test, producción).  

---

## 12. ¿Qué son las herramientas de desarrollo de Chrome y cómo se accede a ellas?
Son un conjunto de utilidades para inspeccionar, depurar y optimizar páginas web.  
Se accede con **F12** o clic derecho → **Inspeccionar**.  

---

## 13. ¿Qué se puede hacer en el panel "Elements"?
- Ver la **estructura HTML y CSS aplicado**.  
- Modificar código en vivo.  
- Probar estilos y depurar errores visuales.  

---

## 14. ¿Cómo se utiliza el panel "Console" y para qué es útil?
- Permite ejecutar **comandos JavaScript** directamente.  
- Muestra **mensajes, errores y logs** del código.  
- Útil para **depuración rápida** y pruebas interactivas.  

---

## 15. ¿Qué información se obtiene del panel "Network"?
- Archivos que carga la página (HTML, CSS, JS, imágenes).  
- Tiempo de carga y rendimiento.  
- Estado de las peticiones (200, 404, etc.).  
Es importante para **optimizar velocidad** y **detectar fallos en recursos**.