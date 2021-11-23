# Reto 01 - Agrega colores usados en las tarjetas

## Objetivos
1. Agregar nuevas variables de color en SCSS
2. Utilizar la consola de desarrollador del navegador para obtener información de los elementos de la página de Matcha.
## Requisitos
- Tener instalado Visual Studio Code.

## Instrucciones

Dentro de las tarjetas de los posts, hay 3 colores distintos para los distintos
textos que tenemos. Usa el devtools para encontrar esos colores y defínelos en
el archivo de `_global.scss`.

<br/>

<details>
  <summary>Posible solución</summary>

Definimos los colores en `_global.scss`:

```scss{7-9}
/** _global.scss */

/** colores */
$dark-green-title: #025157;
$dark-green-text: #135359;
$white: #ffffff;
$gray: #4a4a4a;
$light-gray: #979797;
$light-green: #67b54b;
```

</details>

<br/>

[Siguiente](../reto-02/README.md)