# ✨ Pseudo-Clases y Pseudo-Elementos en CSS ✨

¡Bienvenido/a a este repositorio! Aquí encontrarás ejemplos prácticos y explicaciones sobre el uso de **pseudoselectores** en CSS, ideales para mejorar la presentación y la interacción de tus páginas web. 🚀

## ¿Qué es este repositorio? 📚
Este proyecto está pensado como material de estudio para comprender y practicar el uso de **pseudo-clases** y **pseudo-elementos** en CSS. Incluye ejemplos aplicados a listas, párrafos, formularios y otros elementos comunes en HTML.

---

## ¿Qué son los pseudoselectores? 🕵️‍♂️
Los pseudoselectores permiten seleccionar y dar estilo a partes específicas de los elementos HTML, o a elementos en ciertos estados, que no pueden ser seleccionados solo con selectores tradicionales.

Existen dos grandes grupos:
- **Pseudo-clases** (`:pseudo-clase`)
- **Pseudo-elementos** (`::pseudo-elemento`)

---

## Pseudo-clases más usadas en este proyecto 🟣
Las **pseudo-clases** permiten seleccionar elementos según su estado o posición. Algunos ejemplos del proyecto:

- `:hover` 👉 Aplica estilos cuando el usuario pasa el mouse por encima de un elemento.
- `:first-child` y `:last-child` 👉 Seleccionan el primer o último hijo de un elemento padre.
- `:nth-child(n)` 👉 Selecciona el hijo número "n" de un elemento padre (puede ser par, impar, etc.).
- `:only-child` 👉 Selecciona un elemento que es el único hijo de su padre.
- `:disabled`, `:focus`, `:valid`, `:invalid` 👉 Muy útiles en formularios para resaltar campos según su estado.
- `:link`, `:visited` 👉 Permiten diferenciar enlaces no visitados de los ya visitados.

**Ejemplo:**
```css
a:hover {
  text-decoration: underline;
}
input:focus {
  outline: none;
}
li:nth-child(odd) {
  background: #e5e5e5;
}
```

---

## Pseudo-elementos destacados en este proyecto 🟢
Los **pseudo-elementos** permiten seleccionar y dar estilo a una parte específica de un elemento.

- `::before` y `::after` 👉 Permiten insertar contenido antes o después de un elemento, útil para iconos, viñetas, decoraciones, etc.
- `::selection` 👉 Permite cambiar el estilo del texto seleccionado por el usuario.
- `::first-line` 👉 Aplica estilos solo a la primera línea de un párrafo.
- `::placeholder` 👉 Da estilo al texto de ayuda en los campos de formulario.

**Ejemplo:**
```css
h1::selection {
  background-color: deeppink;
}
.required::after {
  content: "*";
  color: red;
}
.dialogo::after {
  content: url("../img/perro.gif");
}
```

---

## ¿Dónde los veo en acción? 👀
- **Listas rayadas:** alternan colores con `:nth-child(odd)` y `:nth-child(even)`.
- **Enlaces:** cambian de color y subrayado con `:hover`, `:link`, `:visited`.
- **Formularios:** los campos muestran diferentes estilos según su validez o estado (`:focus`, `:valid`, `:invalid`, `:disabled`).
- **Decoraciones:** se agregan iconos y viñetas con `::before` y `::after`.
- **Textos seleccionados:** el color de fondo cambia con `::selection`.

---

## ¿Por qué son importantes? 💡
Los pseudoselectores permiten crear interfaces más atractivas, accesibles y dinámicas, mejorando la experiencia del usuario sin necesidad de JavaScript.

---

## Recursos recomendados 📖
- [MDN Web Docs: Pseudo-clases](https://developer.mozilla.org/es/docs/Web/CSS/Pseudo-classes)
- [MDN Web Docs: Pseudo-elementos](https://developer.mozilla.org/es/docs/Web/CSS/Pseudo-elements)

---

¡Explora el código y experimenta! 🧑‍💻 Si tienes dudas, revisa los comentarios en el CSS y el HTML para más ejemplos y explicaciones.
