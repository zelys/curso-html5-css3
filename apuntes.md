# Adaptando el CSS

## Buenas Practicas

- En HTML usamos `id` cuando queremos alterar comportamientos y usamos `class` cuando queremos alterar los estilos.

- Los nombres de las clases deben ser representativos, pero no tan especificos, la idea es no asociar comportamientos o estilos a los nombres o nomenclaturas por que esos comportamientos pueden cambiar más adelante.

## ¿Para qué sirve la propiedad float?

Tanto el `float:left` como el `float: right` sirven para que el elemento se destaque en la pantalla, la superficie del elemento continúa siendo utilizada y los otros elementos de texto o elementos en línea se posicionan alrededor de él.

## ¿Para qué sirve la etiqueta iframe?

A través de la etiqueta `iframe` podemos insertar diferentes tipos de elementos externos en nuestra página. Sean estos mapas, vídeos, imágenes u otras páginas web o páginas de redes sociales.

## Medidas proporcionales

¿Cómo usar medidas proporcionales para dejar un elemento 100% de ancho con el equivalente a un tercio del elemento padre, menos 10px?

`width: calc( (100% / 3) - 10px )`

## Selectores avanzados CSS

- Selector `>` , para acceder a los hijos de determinado elemento. Por ejemplo, para acceder todos los p dentro del main:

  ```css
  main > p {
  }
  ```

- Selector `+`, para acceder al primer hermano de determinado elemento. Por ejemplo, para acceder el primer p después de una img:

  ```css
  img + p {
  }
  ```

- Selector ~, para acceder a todos los hermanos de determinado elemento. Por ejemplo, para acceder todos los p después de una img:

  ```css
  img ~ p {
  }
  ```

- Selector not, para acceder a los elementos, excepto algunos. Por ejemplo, para acceder a todos los p dentro de main excepto el p que tiene id mission:

  ```css
  main p:not(#mission) {
  }
  ```

## Meta tag de Viewport

¿Qué significa que nuestra página sea responsiva? Nuestra página que sea responsiva significa que al momento de ser abierta desde cualquier dispositivo, sea un monitor grande, una pantalla de una notebook, una PC, o un monitor de un dispositivo celular o una tablet, consiga adaptarse al tamaño en forma adecuada.

## Fuentes Externas

**Contenido referencial**: _fonts.google.com_

## Inputs para celulares

**Contenido referencial**: _mobileinputtypes.com_

**Documentación HTML - CSS**: _developer.mozilla.org_
