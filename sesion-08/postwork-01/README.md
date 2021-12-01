**Front-End Fundamentals**

**POSTWORK**

Sesión 08

**Interactividad básica (transiciones y animaciones)**

**Objetivo**

- Desarrollar botones con transiciones.

**Antes de empezar**

En esta sección encontrarás algunos tips por si algún recurso mostrado viene en otro idioma y encontrarás la instalación necesaria para tu módulo.


Algunos recursos están en inglés. Si prefieres leerlos en español, puedes hacer de Google tu traductor predeterminado, quien te ofrecerá la opción de traducir la página que vas a consultar. 

[](../assets/traducir-pagina.png)

- Otra opción es usar un traductor desde cualquier buscador. 
[](../assets/traductor-google.png)


Encontrarás videos **que no están en español.** Si deseas activar los subtítulos 💬   en **YouTube**,  realiza los siguiente pasos:

- Busca el logo de **configuración** (⚙️) dentro de la ventana del video.
- ` `Haz click ahí y selecciona **Subtítulos.**
- ` `Haz click en **Activar.**
###
**⚙️ Setup**

A continuación te mostramos  las instalaciones necesarias para tu módulo:

**Editor de código.**

- [Visual Studio Code ](https://code.visualstudio.com/download)

**Versionamiento de código.**

- [Git ](https://git-scm.com/downloads)
- Tener una cuenta de [GitHu](https://github.com/)b

### **Desarrollo**
¡Hemos llegado al final del módulo! Hace un mes, posiblemente sabías muy poco o nada sobre el desarrollo HTML y CSS, pero ahora ya conoces esos dos lenguajes con la suficiente profundidad como para continuar con este proceso de aprender desarrollo web. 

Ahora te damos un nuevo desafío con lo que aprendiste en clase, que te permitirá familiarizarte aún más con los elementos de CSS como son las transiciones y animaciones. Todavía hay mucho material que obtendrás con Bedu, así que ¡esto apenas empieza!


**🎞 Video 01.**  Tutorial - Botones animados en tu desarrollo

En el siguiente [video](https://www.youtube.com/watch?v=c-4wFMGFuCg) aprenderás a crear botones animados que podrás utilizar en tu desarrollo de clase. Recuerda que debes utilizar el color **#025157** como primer estado, y después usar el color **#67b54b** para el estado en **:hover**.

[Botones animados](https://www.youtube.com/watch?v=c-4wFMGFuCg)

**¡Recapitulemos!**

- Al finalizar este postwork, todos los botones de tu desarrollo deben tener alguna transición. Esto se logra aplicando los elementos que aprendiste sobre transiciones y aplicando los estilos de CSS adecuados para llegar a esta meta.

**¡Happy coding 💻!**
<br/>
<br/>

**Respuesta**

Estos son los estilos y código aplicado a nuestro proyecto cuando usamos el primer botón que aparece en el video. Trata de llegar a ellos a través del estudio personal del video.

**HTML**

```html
<button *type*="submit" *class*="texto-boton uno">
<span>Try it now &rarr;</span>
</button>
```
<br/>

Este mismo patrón debe estar presente en todos los demás botones de nuestro desarrollo para que puedas observar el efecto de transición.

<br/>

**CSS**

Debemos agregar algunas propiedades a nuestro estilos del botón, y recordar que el diseño que hicimos es un poco diferente al que se presenta el video, con lo que no todo lo que ves en el video lo debes aplicar aqui.

Recuerda, esta es la manera que te recomendamos solucionar este desafío, pero trata de seguir con el video y utilizar tal vez las demás transiciones que ahí se presentan.
<br/>

```css

.texto-boton {
font-size: 1rem;
height: 100%;
padding: 6px 20px;
margin-left: -10px;
color: #fff;
background-color: #025157;
border-radius: 8px;
border: none;
border-top-left-radius: 0;
border-bottom-left-radius: 0;
position: relative;
overflow: hidden;

}

.texto-boton span {
position: relative;
z-index: 2;

}

.texto-boton.uno::after {
content: " ";
width: 100%;
height: 100%;
background: #67b54b;
position: absolute;
top: -100%;
left: 0;
z-index: 1;
transition: 0.3s ease-in-out all;

}

.texto-boton.uno:hover::after {
top: 0;

}

```

<br />
<br />

✅ **Checklist**

Asegúrate que tu postwork contenga todo lo siguiente, ya que esto se evaluará al término del módulo. Recuerda que los elementos que debes cambiar son los botones en la sección “Publicidad” y “Blog”.


|**Requisito**|**Sí lo cumple**|**No lo cumple**|
| :-: | :-: | :-: |
|A. Cambiar los botones normales por unos con transición|||
|B. Utilizar elementos de transición o animación, según corresponda por el número de estados.|||

[Regresar](../)
