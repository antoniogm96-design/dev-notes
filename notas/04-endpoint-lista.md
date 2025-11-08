---
title: "Paso 4: Creando el Endpoint de la Lista"
publishDate: "2025-11-08"
summary: "El siguiente paso es crear un archivo JSON que liste todas mis notas y sus URLs."
---

# Creando el Endpoint de la Lista de Notas

Ya tengo varias notas individuales. Ahora necesito un "índice" o un endpoint que le diga a los demás dónde encontrarlas todas.

El plan es crear un archivo `notes-list.json`. Este archivo contendrá una lista (un array) de objetos, donde cada objeto representará una de mis notas, incluyendo su título, resumen y, lo más importante, la URL directa a su contenido "raw" en GitHub.
