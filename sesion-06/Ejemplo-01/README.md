# Ej. 01 - Agregando javascript al proyecto

## Introducción

El framework de Bootstrap también utiliza un lenguaje de programación para lograr que algunos de sus elementos puedan funcionar correctamente. Este paso dentro de tu proyecto es importante para que la funcionalidad que necesitas se encuentre presente siempre.
## Objetivos
1. Insertar los scripts de Javascript que utiliza Bootstrap.

## Requisitos

1. Tener instalado Visual Studio Code.

## Desarrollo

## Cómo agregar iconos

Para insertar un ícono, agregue el nombre de la clase de ícono a cualquier elemento HTML en línea.

Los elementos `<i>` y `<span>` se utilizan ampliamente para agregar iconos.

Todos los íconos en las bibliotecas de íconos a continuación son íconos vectoriales escalables que se pueden personalizar con CSS (tamaño, color, sombra, etc.)

Algunas alternativas para usar iconos son:

- Font Awesome

```html 
<!DOCTYPE html>
<html>
  <head>
    <script src="https://kit.fontawesome.com/yourcode.js" crossorigin="anonymous"></script>
  </head>
  <body>

    <i class="fas fa-band-aid"></i>
    <i class="fas fa-cat"></i>
    <i class="fas fa-dragon"></i>
    <i class="far fa-clock"></i>
    <i class="fas fa-clock"></i>

  </body>
</html>

```

- Bootstrap 3

```html
<!DOCTYPE html>
<html>
  <head>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
  </head>
  <body>

    <i class="glyphicon glyphicon-cloud"></i>
    <i class="glyphicon glyphicon-remove"></i>
    <i class="glyphicon glyphicon-user"></i>
    <i class="glyphicon glyphicon-envelope"></i>
    <i class="glyphicon glyphicon-thumbs-up"></i>

  </body>
</html>
```

- Google

```html
<!DOCTYPE html>
<html>
  <head>
    <link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons">
  </head>
  <body>

    <i class="material-icons">cloud</i>
    <i class="material-icons">favorite</i>
    <i class="material-icons">attachment</i>
    <i class="material-icons">computer</i>
    <i class="material-icons">traffic</i>

  </body>
</html>
```

[Siguiente](../reto-01)