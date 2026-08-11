# Canvas API

## ¿Qué es?

La Canvas API permite crear y dibujar gráficos directamente en una página web utilizando JavaScript.

El elemento HTML utilizado es:

```html
<canvas>
```

Por sí solo, el elemento canvas funciona como un área donde se pueden realizar dibujos mediante JavaScript.

## ¿Para qué sirve?

Canvas puede utilizarse para crear:

- Gráficos.
- Dibujos.
- Animaciones.
- Juegos.
- Elementos interactivos.

## ¿Cómo funciona?

Primero se crea un elemento `<canvas>` en HTML.

Después, mediante JavaScript, se obtiene su contexto de dibujo utilizando:

```javascript
getContext("2d")
```

A partir de este contexto se pueden dibujar diferentes formas.

## Ejemplo

El ejercicio crea un canvas y dibuja un rectángulo utilizando JavaScript.

## Fuente

https://www.w3schools.com/html/html5_canvas.asp