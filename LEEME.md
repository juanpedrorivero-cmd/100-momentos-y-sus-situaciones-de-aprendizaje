# Historia de Canarias · 100 momentos y situaciones de aprendizaje

Dos obras colectivas del alumnado de Didáctica de las Ciencias Sociales I (Grado en Maestro/a en Educación Primaria,
Universidad de La Laguna, curso 2026/2027), coordinadas por Juan Pedro Rivero González.

Publicadas en **https://juanpedrorivero-cmd.github.io/100-momentos-canarias-y-situaciones-aprendizaje/**

1. **100 momentos de Historia de Canarias.** Línea temporal con cien procesos y acontecimientos: 90 investigados
   por el alumnado y 10 por la edición docente (21, 27, 49, 53, 60, 73, 79, 90, 91 y 96).
2. **Situaciones de aprendizaje para enseñar la Historia de Canarias.** 81 propuestas para Educación Primaria: cada
   estudiante convirtió el trabajo histórico de un compañero o compañera en una situación de aprendizaje.

Al abrir un momento o una situación se muestra **su fragmento del documento original**, tal como está maquetado: la
web no reescribe los trabajos.

## Qué hay en el repositorio

| Archivo | Para qué |
|---|---|
| `index.html` | Portada: se elige a qué obra entrar. |
| `100-momentos.html` | Los 100 momentos. |
| `situaciones-aprendizaje.html` | Las situaciones de aprendizaje. |
| `paginas-momentos-1/`, `paginas-momentos-2/` | Páginas del documento de los 100 momentos, como imagen (`m007.webp` … `m166.webp`). |
| `paginas-situaciones-1/` a `-3/` | Páginas del documento de las situaciones (`s002.webp` … `s216.webp`). |
| `social.png`, `social-situaciones.png` | Imágenes que aparecen al compartir el enlace. |

Las dos obras se enlazan entre sí con la barra de arriba («100 momentos de Historia de Canarias / Situaciones de
aprendizaje»), y el pie de cada una lleva a la portada. Los enlaces son relativos: la web funciona con cualquier nombre
de repositorio y también abriendo `index.html` en un ordenador.

Si al subir a GitHub las imágenes quedan sueltas en la raíz, sin su carpeta, la web las busca allí y funciona igual:
cada imagen lleva delante la letra de su obra (`m` o `s`), así que no se confunden.

La web es estática: no hay nada que se ejecute en GitHub.

## Publicar en GitHub Pages

En el repositorio: **Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: `main` /
`(root)` → Save**. El repositorio tiene que ser público. En uno o dos minutos la web está en la dirección de arriba.

## Qué decide la web y no los documentos

- **100 momentos**: los hilos de larga duración, los nombres cortos y etiquetas de los bloques, y la ficha académica
  (resumen, palabras clave y cita). El resumen y las palabras clave se redactaron a partir de la introducción del
  documento: conviene que los revise el coordinador.
- **Situaciones**: los diez temas y qué situaciones agrupa cada uno (agrupación orientativa a partir de títulos y
  preguntas guía), el tipo de producto final (detectado por palabras; cuando el documento no lo nombra, la web pone una
  etiqueta breve con la nota «Descripción de la edición web») y la isla de las situaciones que tratan una isla concreta.
- La web nombra y enlaza la Universidad de La Laguna, pero no usa su logotipo ni su identidad visual: eso requiere
  autorización de la universidad y daría a entender que es una página oficial.

## Antes de hacerla pública

- El documento de los 100 momentos advierte que hay que verificar procedencia, licencia y derechos de reproducción de
  cada imagen antes de una publicación abierta; lo mismo vale para las imágenes de las situaciones. GitHub Pages es
  público.
- El documento de las situaciones pide revisar los casos dudosos de autoría antes de la edición pública. La web
  muestra la autoría tal como viene: sin nombre, o con el nombre y «sin confirmar».

## Cuando llegue una edición nueva

Las dos webs se generaron a partir de los documentos en Word con un generador en Python que no va en este
repositorio. Para una edición nueva hay que volver a generar la obra correspondiente y subir el resultado.

## Dependencias externas

Solo las tipografías (Ibarra Real Nova y Archivo, desde Google Fonts).
