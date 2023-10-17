# Nivel 1: Fundamentos de JavaScript

**Tema 1: HTML.**
En este primer nivel se verán los fundamentos de HTML, qué es, para que sirve y cómo se relaciona con React. Se hablará de la definición de JSX para posteriormente profundizar más en ella.

**Esto es HTML:**

```html
<button onclick="alert('Soy un boton HTML')">Presioname!</button>
```

**Esto es JSX:**

```jsx
<>
  <Button
    onClick={() => {
      alert("Soy un componente JSX");
    }}
  />
</>
```

**Tema 2: Introducción a JavaScript.**
Después se hablará de JavaScript como tal. Variables (globales, locales), constantes, operadores, estructuras de control, qué son, para que sirven, cómo se usan, por qué se usan, cuándo usar unas y cuando usar otras.

```javascript
var global_var = 5;
let local = 6;
const siempre_igual = global_var + local; // ? 11
```

**Tema 3: Flujo de datos en JavaScript**
Se hablará de las funciones, el alcance de las variables y se presentarán los Objetos de JavaScript (JSON), qué son, para qué sirven, cuándo usarlos y buenas prácticas para el uso de los objetos.

```javascript
function clasica() {
  acciones_aqui(); // ? Aqui se ponen las intrucciones
}

const moderna = () => {
  arrow_function(); // ? Aqui se ponen las intrucciones
};

const obj_json = {
  // ? Este es un objeto de JavaScript (JSON)
  name: "Yael",
  age: 20,
  languages: [
    "JavaScript",
    "TypeScript",
    "PHP",
    "GDScript",
    "Python",
    "Kotlin",
  ],
};
```

**Tema 4: DOM, (HTML y JS)**

Por último, se explicará qué es el DOM, su funcionamiento, estructura de un DOM y la relación de los enlaces.

```html
<!-- Aqui empieza el DOM -->
<!DOCTYPE html>
<html>
  <head>
    <!-- ENLACES AQUI -->
  </head>
  <body>
    <!-- CONTENIDO AQUI -->
  </body>
</html>
<!-- Aqui termina el DOM -->
```
