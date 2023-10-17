## Tema 1: HTML

### Qué es un lenguaje de etiquetas?

Un lenguaje de etiquetas, también conocido como lenguaje de marcas, es una forma de codificar un documento que, junto con el texto, incorpora etiquetas o marcas que contienen información adicional acerca de la estructura del texto o su presentación. Estas etiquetas son bloques de código que dan formato, funcionalidad y estructura al contenido de las páginas web.

Un ejemplo muy conocido de un lenguaje de etiquetas es el **HTML** (Lenguaje de Marcas de Hipertexto, del inglés **HyperText Markup Language**). **HTML** es el componente más básico de la Web y define el **significado y la estructura** del contenido web. Dicho en otras palabras, un documento **HTML** es el esqueleto o los cimientos de nuestra página web. Las etiquetas HTML son un estándar adoptado por todos los desarrolladores que, mediante etiquetas, les permite a los navegadores interpretar los elementos de una página web.

<img src="./img/html.gif" style="display:block; text-align:center; margin:auto;"/>

### Qué son las etiquetas?

Las etiquetas **HTML** son instrucciones que indican cómo mostrar el contenido en una página web. Cada etiqueta HTML se compone de tres partes:

- Una etiqueta de apertura, que empieza con un símbolo `<` y contiene el nombre del elemento y sus atributos.
- El `contenido`, que es el texto o el código que se muestra entre la etiqueta de apertura y la de cierre.
- Una etiqueta de cierre, que termina con un símbolo `>` y contiene el nombre del elemento precedido por una barra `/`.

Existen muchas etiquetas **HTML**, cada una con su propio propósito y función. Algunas etiquetas comunes incluyen:

1. `<html>`: Define el inicio y fin del documento **HTML**.
2. `<head>`: Define la información de encabezado del documento, como el título y los metadatos.
3. `<body>`: Define el contenido principal del documento.

<img src="./img/labels.gif" style="display:block; text-align:center; margin:auto;"/>

Es importante mencionar que el **HTML** no se considera un lenguaje de programación, pues no crea funciones dinámicas. Sin embargo, con el apoyo de las etiquetas, se pueden configurar diversas estructuras para sitios web; por ejemplo: secciones, tablas, párrafos, enlaces, atributos y otros elementos que compondrán una página web, como imágenes, listas, vídeos, etc.

**HTML** se escribe en un documento de texto, con una extensión `.html` o `.htm`. Cada etiqueta tiene una forma como `<b>` o `<p>`, y casi todas tienen una etiqueta de cierre como `</b>` o `</p>`. Por ejemplo:

- `<b>Esto está en negrita</b>`

Se muestra como:

- **Esto está en negrita**.

**HTML** se creó en 1993 y desde entonces ha evolucionado con **diferentes versiones** y estándares. La versión más reciente es **HTML5** (con la que estaremos trabajando), que incorpora nuevas funcionalidades y mejoras para la web.

## Estructura básica

Un documento **HTML** básico tiene la siguiente estructura:

```html
<!DOCTYPE html>
<html>
  <head>
    <!-- Aqui se incluyen enlaces a otros archivos importantes (como hojas de estilos y scripts) -->
    <title>Título de la página</title>
  </head>
  <body>
    <!-- Aqui es donde se estructura el contenido -->
    <h1>Este es un encabezado h1</h1>
    <p>Este es un párrafo.</p>
    <a href="https://www.ejemplo.com">Este es un enlace</a>
    <img
      src="./react-logo.png"
      alt="Descripción de la imagen"
      title="Esta es una imagen"
    />
    <div>Este es un div, que es un contenedor genérico.</div>
  </body>
</html>
```

- `<!DOCTYPE html>`: Define el tipo de documento y la versión de HTML.
- `<html>`: Es la etiqueta raíz de una página HTML.
- `<head>`: Contiene metainformación sobre el documento HTML, como el titulo y enlaces.
- `<title>`: Define el título del documento, que se muestra en la barra de título del navegador.
- `<body>`: Contiene el contenido principal del documento HTML.
- `<h1>` a `<h6>`: Definen los encabezados. `<h1>` es el encabezado más grande y `<h6>` es el más pequeño.
- `<p>`: Define un párrafo.
- `<a>`: Define un enlace. El atributo `href` especifica la URL de la página a la que enlaza.
- `<img>`: Define una imagen. El atributo `src` especifica la ruta de la imagen y `alt` proporciona una descripción alternativa para la imagen.
- `<div>`: Define una sección en un documento.

<br /><br />

**Ejemplo del código anterior:**

<!DOCTYPE html>
<html>
    <head>
        <title>Título de la página</title>
    </head>
    <body>
        <h1>Este es un encabezado h1</h1>
        <p>Este es un párrafo.</p>
        <a href="https://www.ejemplo.com">Este es un enlace</a>
        <img src="./img/react-logo.png" alt="Descripción de la imagen" title="Esta es una imagen">
        <div>Este es un div, que es un contenedor genérico.</div>
    </body>
</html>

<br /><br />

## Etiquetas más comunes de HTML

Aquí te presento algunas de las etiquetas HTML más comunes que se utilizan en el desarrollo web:

1. **Etiquetas iniciales o de raíz**:

   - `<!DOCTYPE html>`: Indica al navegador que el documento está basado en el estándar HTML5.
   - `<html></html>`: Representa la raíz de un documento HTML. Todos los demás elementos de la estructura HTML deben ser recogidos dentro de estas etiquetas.

2. **Metadatos del documento**:

   - `<head></head>`: Representa una colección de metadatos acerca del documento, incluyendo enlaces a, o definiciones de, scripts y hojas de estilo.

3. **Etiquetas de texto**:

   - `<p></p>`: Define un párrafo.
   - `<h1></h1> a <h6></h6>`: Define encabezados, donde `<h1>` es el encabezado más importante y `<h6>` es el menos importante.
   - `<strong></strong>`: Define texto en negrita.
   - `<em></em>`: Define texto en cursiva.

4. **Etiquetas multimedia**:

   - `<img>`: Inserta una imagen.
   - `<video></video>`: Inserta un video.
   - `<audio></audio>`: Inserta un audio.

5. **Etiquetas para estructurar el contenido**:

   - `<div></div>`: Define una sección en un documento.
   - `<span></span>`: Se utiliza para agrupar elementos en línea en un documento.

6. **Etiquetas para crear tablas**:

   - `<table></table>`: Define una tabla.
   - `<tr></tr>`: Define una fila en una tabla.
   - `<td></td>`: Define una celda en una tabla.

7. **Etiquetas para crear formularios**:
   - `<form></form>`: Define un formulario HTML para entrada del usuario.
   - `<input>`: Define un campo de entrada controlado por el usuario.

Estas son solo algunas de las etiquetas **HTML** más comunes. Existen muchas más que puedes explorar para desarrollar sitios web más complejos y funcionales. Aquí un ejemplo en código y su resultado:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Ejemplo</title>
    <style>
      /* ESTA ETIQUETA SIRVE PARA DAR ESTILOS (CON CSS) DENTRO DEL MISMO DOCUMENTO */
      .titles {
        text-align: center;
        background-color: black;
        color: yellow;
        border-radius: 15px;
      }
    </style>
  </head>

  <body>
    <div class="titles">
      <!-- Esta es la etiqueta div (estructural) a la que se le están aplicando los estilos -->
      <h1>Soy un titulo h1</h1>
      <h2>Soy un subtitulo h2</h2>
      <h3>Soy un subtitulo h3</h3>
      <h4>Soy un subtitulo pequeño h4</h4>
      <h5>Soy un subtitulo más pequeño h5</h5>
      <h6>Soy el subtitulo más pequeño de todos h6</h6>
      <!-- Todas estas son las etiquetas para texto que se aplican a los titulos -->
    </div>
    <p>
      Este es un <b>parrafo</b> que describe y <em>ejemplifica</em> cómo
      funcionan las etiquetas HTML.
    </p>
    <form>
      <input type="text" placeholder="Escribe tu nombre" />
      <input type="password" placeholder="Escribe tu contraseña" />
      <input type="number" placeholder="Escribe tu numero" />
      <input type="file" placeholder="Elige un archivo" />
      <input type="submit" value="Guardar" />
    </form>
  </body>
</html>
```

<br/><br/>
**Este es el resultado del código anterior**:

<!DOCTYPE html>
<html>
  <head>
    <title>Ejemplo</title>
    <style>
      .titles{
        text-align: center;
        background-color: black;
        color: yellow;
        border-radius: 15px;
      }
    </style>
  </head>

  <body>
    <div class="titles">
      <h1>Soy un titulo h1</h1>
      <h2> Soy un subtitulo h2 </h2>
      <h3> Soy un subtitulo h3 </h3>
      <h4> Soy un subtitulo pequeño h4 </h4>
      <h5> Soy un subtitulo más pequeño h5 </h5>
      <h6> Soy el subtitulo más pequeño de todos h6 </h6>
    </div>
    <p> Este es un <b>parrafo</b> que describe y <em>ejemplifica</em> cómo funcionan las etiquetas HTML. </p>
    <form>
      <input type="text" placeholder="Escribe tu nombre" />
      <input type="password" placeholder="Escribe tu contraseña" />
      <input type="number" placeholder="Escribe tu numero" />
      <input type="file" placeholder="Elige un archivo" />
      <input type="submit" value="Guardar" />
    </form>

  </body>
</html>

## Atributos mas comunes

Todas las etiquetas en HTML tienen sus atributos. Sobre todo las etiquetas de una línea, etiquetas como `<input/>` o `<img/>`, son etiquetas que su sintaxis es diferente a las demás, ya que no tienen una etiqueta de apertura y una de cierre como en su mayoría. Por ejemplo, una etiqueta h1 que sirve para escribir titulos de texto se escribiría así: `<h1>Soy un titulo</h1>`. A diferencia de una etiqueta para imagenes, se escribiria asi:

- `<img `src`="dirreccion_a_la_imagen" `alt`="Texto_que_sustituye_a_la_imagen" />`

Algunos de los atributos más comunes son:

- **Atributos principales (core attributes):** Estos atributos tienen unas normas: No deben empezar nunca por un número, pero pueden contenerlos más adelante. El texto debe estar en kebab-case, es decir, minúsculas y separados por un guión. Es preferible que no contenga caracteres raros, acentuados o emojis.

  - `id`. Establece un identificador único a la etiqueta **HTML**. Sólo puede existir el mismo nombre una vez por documento.
  - `class`. El atributo `class` sirve para indicar una **clase** de CSS (coleccion de elementos que heredan un conjunto de estilos), que explicaremos más adelante, en el que se atribuyen estilos como colores, tamaños y formas a una, o a varias etiquetas.

- **Atributos globales y particulares:**
  - `title`. Este atributo proporciona un título a un elemento **proporcionando información** sobre el mismo. No todos los elementos pueden usar este atributo, un caso común sería usarlo en un hipervínculo.
  - `src`. En este caso, este atributo se usa para imagenes, para indicar **la ruta** de la imagen.

## Crear una página web básica

En esta sección vamos a crear la `estructura básica` de un documento **HTML**.

<img src="./img/coding.gif" style="display:block; text-align:center; margin:auto;"/>
