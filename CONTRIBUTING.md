# Agregar un proyecto al portafolio

Cada proyecto tiene una ficha Markdown y sus propios recursos. El README
principal funciona como índice y destaca los proyectos publicados.

## Estructura

```text
README.md
assets/cover.svg
projects/
  desert-brew-os/
    README.md
    assets/
      cover.svg
      sales-note-demo.png
templates/project.md
```

## Pasos

1. Crea `projects/nombre-del-proyecto/`. Usa un nombre corto, en minúsculas,
   sin espacios ni acentos, con guiones entre palabras.
2. Copia `templates/project.md` como `README.md` dentro de esa carpeta.
3. Completa la ficha y elimina las instrucciones que estén entre corchetes.
   Cambia el enlace de regreso de `../README.md` a `../../README.md`, porque
   la ficha final estará dentro de `projects/nombre-del-proyecto/`.
   Si una sección no aplica, elimínala.
4. Guarda capturas y portada en la carpeta `assets/` del proyecto. Usa datos
   de demostración o imágenes preparadas para publicación.
5. Agrega una entrada en la sección **Proyectos** del README principal con
   nombre, descripción, tecnologías y enlace a la ficha.
6. Comprueba la visualización de enlaces, imágenes y diagramas en GitHub.
7. Guarda los cambios en un commit y publícalos en este repositorio.

## Criterios de publicación

- Presenta el problema, las capacidades y las decisiones técnicas con ejemplos concretos.
- Identifica si las imágenes provienen de una demostración, un prototipo o una interfaz implementada.
- Distingue lo implementado del trabajo previsto. Incluye métricas solo cuando exista evidencia.
- Usa enlaces relativos a recursos incluidos en este portafolio. Enlaza código externo únicamente cuando sea público y esté destinado a compartirse.
- Revisa las capturas antes de publicarlas y excluye credenciales, datos de clientes y documentos financieros reales.
- Conserva la portada general para mantener una entrada común a todos los proyectos.
