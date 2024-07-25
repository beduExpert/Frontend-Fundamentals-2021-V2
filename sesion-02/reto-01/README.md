# Reto 01 - Etiquetas semánticas para barra de navegación
## Objetivos
- Utilizar etiquetas semánticas en la barra de navegación.
- Agregar los estilos correctos para ajustar el posicionamiento de la barra de navegación.

---
<br/>

### REQUISITOS
- Tener conocimientos básicos de HTML y CSS

---
<br/>

### INSTRUCCIONES

Navega en internet y encuentra tu página favorita, el unico requisito es que ésta tenga una barra de navegación como la que se discutio en el ejemplo. Algunos sitios web podrian ser Facebook, Amazon, LinkedIn, etc.

Observa detenidamente los elementos que forman la barra de navegación de tu sitio web. Qué elementos logras identificar. ¿Cómo agregarías el contenido de la barra de navegación?

Implementa en medida de lo posible la estructura de la barra de navegación del sitio web en HTML.

> Ten en cuenta que no se verá igual que la página, y eso está bien, ya que nos
> estamos enfocando solo en la estructura y luego le daremos los estilos
> necesarios para darle la apariencia esperada.

<br/>

<details><summary>Posible solución</summary>
<p>

```html

<header class="header">
  <!-- Logo con link a la página principal -->
  <a href="/">
    <img src="https://getmatcha.com/wp-content/themes/getmatcha/img/footer_logo.svg" alt="Matcha"/>
  </a>
  <!-- Menú de navegación -->
  <nav>
    <ul>
      <li>Platform</li>
      <li>Pricing</li>
      <li>Customers</li>
      <li>Resources</li>
      <li>About</li>
    </ul>
  </nav>
  <!-- Contenedor de acciones de usuario -->
  <div>
    <a>Sign In</a>
    <button>Start free trial</button>
  </div>
</header>

```

</p>
</details>

<br/>

[Siguiente](../Ejemplo%2002/README.md)