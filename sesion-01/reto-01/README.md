# Reto 01 - Etiquetas con diferente peso jerárquico

1. Agregar textos con diferentes niveles de jeraquía.
2. Insertar un párrafo, usando el atajo de Emmet de VSCode "Lorem"

<br/>

La principal diferencia es el peso semántico que le queremos dar al texto, si
el texto que queremos mostrar no es necesariamente diferente a cualquier otro
texto que tengamos en la web, probablemente un párrafo funcione bien y luego
podríamos cambiar su apariencia para darle los efectos visuales deseados, sin
embargo, si deseamos resaltar dicho texto sobre otros existentes, podemos usar
un encabezado para darle una jerarquía y diferenciarlo de los demás.

Después, insertaremos los elementos que la página de Matcha tiene.
<br/>

<details><summary>Posible solución</summary>
<p>

```html
<!DOCTYPE html>
<html>
  <head>
    <!-- Aquí va información importante pero no visible dentro del navegador -->
    <title>Matcha</title>
  </head>
  <body>
    <!-- Esto es lo que se verá en el navegador web -->
    <h1>Heading level 1</h1>
    <h2>Heading level 2</h2>
    <h3>Heading level 3</h3>
    <h4>Heading level 4</h4>
    <h5>Heading level 5</h5>
    <h6>Heading level 6</h6>
    <!-- Usando un párrafo -->
    <p>
      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin laoreet sem in elit lobortis consectetur. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.
    </p>
  </body>
</html>
```
Ahora, insertemos los elementos de la página de Matcha que imitaremos en nuestro proceso de aprender a elaborar una página web moderna.

```html
  <head>
    <!-- Aquí va información importante pero no visible dentro del navegador -->
    <title>Matcha</title>
  </head>
  <body>
    <h1>Construye tu Blog. Construye tu negocio.</h1>
    <p>Instantly publish articles, drive more traffic, grow your email list, and see your blog's
      impact on sales</p>
  </body>
```

</p>
</details>

<br/>

[Siguiente](../reto-02/README.md)