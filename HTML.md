# REGLAS DE HTML

## Usar Document Type correctamente
- Declarar siempre el Document Type en la primera línea del documento.
- Se puede poner en minúsculas para tener consistencia con las etiquetas en minúsculas.


## Usar minúsculas en las etiquetas
Se recomienda usar minúsculas porque:
- Mezclar minúsculas y mayúsculas es malo.
- Los desarrolladores normalmente usan minúsculas.
- Las minúsculas se ven más limpias.
- Las minúsculas son más fáciles de escribir.

## Cerrar todos los elementos HTML
En HTML5 no necesitas cerrar todos los elementos (por ejemplo el elemento ```<p>```), pero es recomendable hacerlo.

Mal:
```HTML
<section>
  <p>Ésto es un párrafo.
  <p>Ésto es un párrafo.
</section>
```
Bien:
```HTML
<section>
  <p>Ésto es un párrafo.</p>
  <p>Ésto es un párrafo.</p>
</section>
```

## Cerrar elementos vacíos
En HTML5 es opcional cerrar los elementos vacíos, pero es obligatorio en XHTML y XML.

Mal:
```HTML
<meta charset="utf-8">
```
Bien:
```HTML
<meta charset="utf-8" />
```

## Poner comillas a los valores de los atributos
HTML5 permite que no se usen, pero se recomienda porque:
- Los valores entrecomillados son más fáciles de leer.
- DEBES usar comillas si el valor contiene espacios.

## Atributos de las imágenes
- Añadir siempre el atributo "alt" a las imágenes (ésto es importante cuando por alguna razón la imagen no puede ser mostrada).
- También es recomendable definir el ancho y el largo.

## Espacios y signos de igual
- No poner espacios alrededor de los signos igual.

Mal:
```html
<link rel = "stylesheet" href = "styles.css"> 
```
Bien:
```html
<link rel="stylesheet" href="styles.css"> 
```

## Evitar lineas de código largas
- Intentar evitar lineas de más de 80 carácteres.

## Espacios en blanco e indentación
- No añadir lineas en blanco sin razón.
- Por legibilidad, añadir lineas en blanco para separar grandes bloques de código.
- No usar lineas en blanco e indentación inecesaria. No es necesario indentar cada elemento.

## ¿Omitir ```<head>```, ```<html>``` y ```<body>```?
En HTML5 estas etiquetas pueden ser omitidas.

**No se recomienda hacerlo**

## Metadatos
- Hacer el elemento ```<title>``` lo más descriptivo posible.
- El lenguaje y la codificación de carácteres debe ser definida lo antes posible en el documento.

## Comentarios HTML
- Comentarios de una línea:
```HTML
<!-- Esto es un comentario -->
```
- Comentarios de varias líneas:
```HTML
<!--
  This is a long comment example. This is a long comment example.
  This is a long comment example. This is a long comment example.
-->
```

## Hojas de estilo y Scripts
- Usar sintaxis simple para linkear hojas de estilo y scripts.

## Usar minúsculas en los nombres de los archivos
Algunos servidores web son sensibles a mayúsculas y minúsculas en los nombres de archivo, pero otros servidores no lo son.
Pasar de uno a otro podría llevar a errores.

