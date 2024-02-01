# ASIX1_M4_UF1-A3_Apuntes

# Funcionamiento de GIT

1. Nuevo repositorio
Para crear un nuevo repositorio debemos ir al apartado de repositorios y clicar en crear uno nuevo.

En “repository name” ponemos el nombre que queremos que tenga nuestro repositorio clonado.

Cuando creamos un nuevo repositorio, hemos de elegir si queremos que el repositorio sea público o privado. Si posteriormente queremos activar GitHub pages para poder publicar el repositorio (sólo HTML + CSS básico, no PHP) ha de ser público.

Marcamos la opción de creación del archivo README o no, dependiendo de:

Si creamos el archivo README, el repositorio se crea e inicializa automáticamente en GitHub (ver apartado a).


En caso de que no se marque el archivo README.md, el repositorio en GitHub se creará vacío y no inicializado. Eso se usará sobre todo para crear un repositorio nuevo desde cero en local (GIT) y luego sincronizarlo (ver apartado b) o importar un repositorio local que tengamos creado (ver apartado c). Una vez creado, nos aparecerá una “chuleta” con los comandos que hemos de utilizar dependiendo de lo que queramos hacer con él mediante comandos de CLI:



# Introducción a Markdown

Markdown es un lenguaje de marcado ligero y fácil de usar para formatear texto de manera sencilla y legible. A continuación, se presentan las etiquetas básicas de Markdown.

## Encabezados

Los encabezados se utilizan para estructurar el contenido. Markdown proporciona seis niveles de encabezados, donde `#` representa el nivel de encabezado.
# H1
## H2
### H3
#### H4
##### H5
###### H6



##### Estilos de letra
Markdown permite aplicar estilos a texto, como itálica, negrita y combinaciones de ambos.

Este texto esta en *cursiva*.
Este texto esta en _cursiva_.
Este texto esta en **negrita**.
Este texto esta en __negrita__.
Este texto esta en **_negrita y cursiva_**.
Este texto esta ~~tachado~~ (Tachado)

#### Listas

##### Ordenadas
1. Primera opción de menú
2. Segunda opción de menú
3. Terceta opción de menú


##### Desordenadas
* Primera opción de lista desordenada
* Segunda opción de lista desordenada
- Tercera opción de lista desordenada
    1. Primer submenú
    2. Segundo submenú
- Cuarta opción de lista desordenada
    * Tercer submenú
    * Cuarto submenú
+ Quinta opción de lista desordenada
+ Sexta opción de lista desordenada



##### Párrafos
También se puede utilizar triple acento grave para bloques de código con especificación de lenguaje.
```
<html>
    <head>
    </head>
    <body>
        <p>Esto es un parrafo</p>
    </body>
</html>
```

##### Enlaces
[Esto es un enlace](http://joan23.fje.edu "Enlace a la web del cole")

##### Imagenes
![Esto es una imagen](https://github.com/HugoFI/ASIX1M4UF1_A3Apuntes/blob/main/sul.jpeg "Saul")

##### Tablas
|Primera Col.|Seguna Col.|3 Col.|
|---------------|:------------:|---------:|
|Col 2 es|Centrada|35€|
|Col 3 es|Derecha|134€|
|Estilo Cebra|Gris|Blanco|
|Clase|ASIX1|M4|

##### Listas con verificacion
-[ ] Opción A

-[X] Opción B

-[ ] Opción C

# Introducción a HTML
HTML (HyperText Markup Language) es un lenguaje de marcado que define la estructura y contenido de una página web. Se compone de elementos y etiquetas que indican cómo se debe mostrar la información en un navegador.

##### Características de HTML
**HyperText:** Permite enlazar texto con otros contenidos.
**Markup:** Construido mediante etiquetas que envuelven el contenido.
**Language:** Es un lenguaje de marcado, no de programación. Define la estructura de la información.



##### Elementos Básicos de HTML
###### Etiquetas HTML
Las etiquetas se inician entre <> y terminan con </>
en la etiqueta de apertura es donde se pondrán los atributos.


Encabezados:
```
<h1>Encabezado 1</h1>
```

Párrafos:
```
<p>Esto es un parrafo</p>
```
Se pueden sumar las etiquetas poniendo unas dentro de otras
```
<p>Hola <strong>buenos días.</strong></p>
```

Hay etiquetas que no necesitan cerrarse, como por ejemplo de imagen y de separación.
```
<img href="./imagen">
</br>
```

###### Listas:
**Desordenada:**
```
<ul>
  <li>Elemento 1</li>
  <li>Elemento 2</li>
</ul>
```

**Ordenada:**
```
<ol>
  <li>Elemento 1</li>
  <li>Elemento 2</li>
</ol>
```
###### Enlaces
```
<a href="https://ejemplo.com">Enlace</a>
```

**Selectores**
*
.
#


##### Organización del Código HTML
**Comentarios:**
```
<!-- Este es un comentario -->
```

**Sangrado del Código:**
```
<div>
    <div>
        <h1>Titulo</h1>
        <p>Contenido</p>
    </div>
    <div>
        <h1>Titulo</h1>
        <p>Contenido</p>
    </div>
</div>
```

**Organización de Ficheros:**
|--web
| |--imagenes
| | |--img1.png
| |--videos
| | |--video1.mpg
| |--css
| | |--estilo.css
| |--index.html

##### Fontawesome
Darse de Alta:
Font Awesome es una biblioteca de iconos y herramienta de creación de íconos que te permite agregar fácilmente íconos vectoriales escalables. Está diseñada para ser compatible con diferentes tecnologías web, como HTML, CSS y JavaScript.

Añadir Kit's Code al Proyecto:
Este codigo permite usar los iconos de fontawesome en el codigo.
```
<script src="https://kit.fontawesome.com/09f87768b9.js" crossorigin="anonymous"></script>
Añadir Iconos al Proyecto:
```

Este codigo inserta un icono
```
<i class="fa-solid fa-thumbs-up fa-5x"></i>
```

#### Introducción a CSS

###### Fundamentos básicos de CSS.

(X)HTML: La etiqueta DIV

La etiqueta DIV en HTML es de tipo bloque y sirve para crear secciones o agrupar contenidos sin significado semántico. Se puede aplicar estilos CSS para personalizar su apariencia.

```
<html>
<head>
  <style>
    .myDiv {
      border: 5px outset red;
      background-color: lightblue;
      text-align: center;
    }
  </style>
</head>
<body>

<div class="myDiv">
   <h2>This is a heading in a div element</h2>
   <p>This is some text in a div element.</p>
</div>

</body>
</html>
```

**Características de CSS: Historia, ventajas e inconvenientes**
CSS (Cascading Style Sheets) se introdujo para separar la presentación del contenido en la web. Permite definir estilos, diseño y formato para mejorar la estética y la consistencia en un sitio web.

**Ubicación: Cómo incluir CSS (externo, style body y elemento)... prioridad entre ellos.**
Los estilos CSS pueden incluirse de tres maneras: en línea (dentro del elemento HTML), en la cabecera del documento (interno) y en un documento externo. La prioridad varía según la ubicación.

**Sintaxis básica CSS: Estructura, comentarios, agrupar selectores, tipos de selectores, selectores avanzados, composición.**
La sintaxis básica de CSS implica reglas con selectores y declaraciones. Se pueden agrupar selectores, y hay varios tipos de selectores (elementos, clase, id, universales, atributos, hijos, descendientes, hermanos adyacentes). También se pueden usar comentarios y pseudoclases/pseudoelementos.


###### UBICACIÓN
Los estilos se pueden asociar de diferentes maneras a los elementos (X)HTML, ya que se pueden ubicar las propiedades CSS en diferentes ubicaciones.

En la etiqueta (estilo INLINE): Añadiendo las propiedades CSS directamente en el elemento usando el atributo style. Por ejemplo:
```
<p style="text-align:center; color:red">Párrafo centrado rojo</p>
```

En la cabecera del documento (X)HTML (estilo INTERNO): Se pueden poner diferentes propiedades CSS dentro del elemento <style>, dentro del elemento <head> del documento. Por ejemplo:

```
<!DOCTYPE html>
<html lang="ca">
  <head>
    <style> 
      p { 
        text-align:center; 
        color:red;
      } 
    </style>
  </head>
  <body>
    <p>Párrafo centrado rojo</p>
    <p>Párrafo centrado rojo</p>
    <p>Párrafo centrado rojo</p>
  </body>
</html>
```

En un documento externo (estilo externo): Se colocan las propiedades de estilo en un documento externo con extensión .css, y desde el documento (X)HTML se enlaza con esta hoja de estilo con la etiqueta <link> dentro del elemento <head>. Por ejemplo, el documento (X)HTML tendría el siguiente aspecto:

```
<!DOCTYPE html> 
<html>
  <head>
    <link rel="stylesheet" href="estils.css" type="text/css" />
  </head>
  <body>
    <p>Párrafo centrado rojo</p>
  </body>
</html>
```

###### Sintaxis básica CSS
**ESTRUCTURA**
Una hoja de estilos es un conjunto de reglas que definen la estética final de los documentos (X)HTML que la usan. Cada regla está formada por un selector y un conjunto de declaraciones.

Una declaración está formada por una propiedad y su valor asociado.

Un selector sirve para definir a qué elemento o elementos queremos aplicar las declaraciones de la regla. Las declaraciones son las diversas características que han de cumplir los elementos que concuerdan con el selector. A cada propiedad de cada declaración le ponemos el valor que sea necesario.

```
selector { 
  declaración_1;
  ... 
  declaración_n;
}
```

Por ejemplo:
```
p {
  color: black;
  background-color: red;
}
```

**COMENTARIOS**
Al igual que en HTML, se pueden agregar comentarios al código poniéndolos entre /* y */ y pueden ocupar varias líneas.

```
/* Estos son selectores de elementos básicos */
selector {
  propiedad1: valor;
  propiedad2: valor;
  propiedad3: valor;
}
```

##### Selectores Avanzados

###### Selectores Universales

Sirven para seleccionar todos los elementos de la página. En el ejemplo, todos los elementos han de tener un borde sólido negro de un píxel:

```
css
* {
   border: 1px solid #000000;
}
```

Selectores de Atributos
Permiten seleccionar elementos en función de los atributos que contienen. En el ejemplo, quedan afectados todos los elementos <img> con un atributo "alt".

```
img[alt] {
   border: 1px solid #000000;
}
```

Es más útil si se especifica el valor del atributo:
```
img[src="alert.gif"] {
   border: 1px solid #000000;
}
```


Selectores de Hijos
Para seleccionar elementos concretos que son hijos DIRECTOS de otros elementos concretos. Por ejemplo, esta regla pone de color azul el texto de los elementos <strong> que son hijos de <h3> pero no el resto de elementos <strong>.

```
h3 > strong {
   color: blue;
}
```

###### Selectores de Descendientes
Similar al selector de hijos pero selecciona los elementos pertinentes EN CUALQUIER PUNTO de la jerarquía del elemento.

Selectores de Hermanos Adyacentes
Permiten seleccionar un elemento concreto que aparece DIRECTAMENTE DESPUÉS de otro elemento concreto al mismo nivel de la jerarquía del elemento. Por ejemplo, si quisiéramos reducir el espacio vertical entre el <h1> y el primer <h2> pero no afectar al segundo <h2> en el código siguiente:


```
<h1>Encabezado 1 </h1>
<h2>Encabezado 2 (hermano adyacente) </h2>
<h2>Encabezado 2 (hermano no adyacente) </h2>
```

Definiríamos la regla siguiente:

```
h1 + h2 {
   margin-top: -5mm;
}
```


**Pseudoclases**
Se utilizan para definir estilos para los diversos estados de los elementos:

:link: El estado normal por defecto de los enlaces.
:visited: Enlaces que ya se han visitado con el navegador que se está utilizando.
:focus: Enlaces que tienen en ese momento el cursor en su interior.
:hover: Enlaces que tienen en este momento el puntero del ratón sobre ellos.
Pseudoelementos
Como las pseudoclases, no afectan a todo el elemento sino que permiten añadir estilos a UNA PARTE CONCRETA del documento. Por ejemplo, el pseudoelemento ::first-line selecciona solo la primera línea del elemento especificado por el selector.

```
p::first-line {
   color: red;
}
```

Dependiendo del navegador y su versión, se pueden usar tanto :: como : para la selección del pseudoelemento. En navegadores actuales y que soporten CSS3, los dos puntos dobles están aceptados y ayudan a separarlos visualmente de las pseudoclases.



###### Uso de Google Fonts


## Google Fonts

En [Google Fonts](https://fonts.google.com/) localizamos la familia de fuentes que queremos añadir. Entramos en ella y la añadimos con el "+" a la derecha.

Esto hará que nos muestre a la derecha el código que hemos de insertar en la sección head de nuestro HTML en dos formatos, link e @import (para poner en una hoja de estilos externa). Justo a continuación aparecen también las reglas CSS que hemos de añadir al estilo para que el párrafo use la tipografía seleccionada.

Un ejemplo de código sería el siguiente (incluye también un icono de Fontawesome):

```
html
<!doctype html>
<html>
    <head>
        <!-- Inserción de origen de Fontawesome-->
        <script src="https://kit.fontawesome.com/09f87768b9.js" crossorigin="anonymous"></script>

        <!-- Opción 1 para insertar Google Fonts -->
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Edu+VIC+WA+NT+Beginner:wght@400;500&family=Roboto:wght@400;500&display=swap" rel="stylesheet">
        
        <!-- Opción 2 para insertar Google Fonts, el @import se puede poner en un archivo CSS externo -->
        <style>
            @import url('https://fonts.googleapis.com/css2?family=Edu+VIC+WA+NT+Beginner:wght@400;500&family=Roboto:wght@400;500&display=swap');
        </style>
    </head>
    <body>
        <!-- Elemento de Fontawesome -->
        <i class="fa-solid fa-arrow-right-to-bracket fa-2xl"></i> 
        <!-- Insertar estilo de Google Fonts -->
        <p style="font-family: 'Edu VIC WA NT Beginner', cursive; font-size:30px" >chess game</p>
    </body>
</html>
```