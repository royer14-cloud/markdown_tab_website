# Modo de uso

## Estructura general

Para escribir en el software **Markdown Tab**, puedes seguir una estructura clara que incluya metadatos, 
ejemplos de uso y explicación de las funcionalidades específicas. Aquí tienes un ejemplo de redacción para el documento:

<pre><code>
---
title:
autor:
BPM:
---

:::drawchord
Am
:::

 ```chordinbox
 ```

 ```tab
 |--2
 ----3
 ```

## Verse 1
Am
Solo estas
/repeat{Repetir Verse 1}{2}

/newpage
</pre></code>

**Explicación de la estructura**
 - Metadatos (---title, autor, BPM---): Estos campos permiten definir información básica de la canción, como título, autor y tempo.
 - Acordes visuales (:::drawchord Am:::): Permite insertar acordes directamente en el texto para facilitar la lectura musical.
 - Acordes no visuales (`chord{Am}{pos}`): Permite insertar acordes en texto dentro de una caja aleatoria de colores, {pos} es la posicion horizontal en numero donde se escribirá. 
 - Tablatura (tab): Dentro de este bloque puedes escribir tus tablaturas
 - Versos y secciones (## Verse 1): Divide la canción en partes claras, facilitando la lectura y el uso.
 - Repetición (/repeat{...}{n}): Indica que una sección debe repetirse y el n indica la posicion horizontal donde desees escribirlo.
 - Nueva página (/newpage): Inserta un salto de página para organizar mejor el cancionero.

## Uso recomendado
 - Usa la estructura para organizar canciones de forma clara y legible.
 - Aprovecha las etiquetas especiales para acordes, tablaturas y repeticiones.
 - Personaliza los metadatos según la canción que estés documentando.

Esta estructura facilita la creación de cancioneros digitales bien organizados y fáciles de usar para músicos y cantantes.
