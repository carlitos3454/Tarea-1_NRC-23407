# Tarea-1_NRC-23407
Programación Integrativa Componentes Web - Crea tu primer pagina html.
# Mi sitio Web - Carlos Yánez

Este sitio web personal fue desarrollado como parte de la materia **Programación Integrativa Componentes Web (23407)**.
 
 A continuación se describe cada sección del archivo `index.html`.

## Estructura del documento HTML

### `<head>`

```html
<head>
  <meta charset="UTF-8">
  <title>Mi sitio Web.Carlos.Yanez</title>
  <link rel="stylesheet" href="estilo.css">
</head>
```

- `<meta charset="UTF-8">`: Establece la codificación de caracteres
 para que se puedan mostrar correctamente tildes y caracteres especiales.

- `<title>`: Define el título que aparece en la pestaña del navegador.

- `<link rel="stylesheet" href="estilo.css">`: Enlaza el archivo de estilos CSS externo.

    ---CONTENIDO------------

## Contenido principal `<body>`

   ----TITULO PRINCIPAL UTILIZANDO LA ETIQUETA h1----------

### Título principal

```html
<h1>Programación Integrativa Componentes Web 23407 - Carlos Yánez</h1>
```
Es el encabezado principal de la página. Se indica la materia, mi nombre y el curso al que pertenezco.

------ PARRAFOS DESCRIPTIVOS UTILIZANDO LA ETIQUETA <p>------------------

### Párrafos descriptivos
Dichos parrafos son designados para describir el uso de la funcionalidad "<p>"
```html
```
Se brinda mi información basica personal.

----------USO DE UNA IMAGEN USANDO LA ETIQUETA <img --------------------

### Imagen

```html
<img src="espe.jpeg" alt="Logo ESPE">
```
Aqui busco mostrar una imagen que debe estar guardada localmente con el nombre `espe.jpeg`.
El atributo `alt` proporciona un texto alternativo.

---
----------------USO DE ENLACE QUE DIRECCIONA A PAGINA EXTERNA EN ESTE CASO PAGINA DE LA UNIVERSIDAD-------


### Enlace

```html
<a href="https://www.espe.edu.ec/" target="_blank" class="boton">Universidad de las Fuerzas Armadas</a>
```

- El enlace dirige al sitio oficial de la **Universidad de las Fuerzas Armadas ESPE**.
- Se abre en una nueva pestaña (`target="_blank"`).
- Se estiliza como botón con la clase `boton` (definida en el CSS).

---
--------- BLOQUE DE LISTAS ORDENDAS Y DESORDENADAS------------

## Sección de Listas

```html
<section>
```
Aqui se busca agrupa las listas de películas y canciones favoritas a mi preferencia.
### Películas favoritas (lista ordenada)

-----USO DE LA LISTA ol-----
```html
<ol>
  <li>Rápidos y Furiosos</li>
  ...
</ol>
```
Muestra una lista numerada de mis películas favoritas.

------USO DE LA LISTA ul--------

### Canciones favoritas (lista desordenada)

```html
<ul>
  <li>Bad Bunny - KLOuFRENS</li>
  ...
</ul>
```
Muestra una lista sin numeración de mis canciones favoritas.

---

## Archivos relacionados como hoja de estilo y imagen jpeg.

- `index.html`: Archivo principal con el contenido de la página.
- `estilo.css`: Archivo externo con los estilos visuales que aplique a la página.
- `espe.jpeg`: Imagen que esta en la misma carpeta del proyecto.

---
