# Club de la IA
----------------------------------

Este documento contiene la información básica de las sesiones que se vayan celebrando en torno a este club, así como un historial para ver el avance de las diferentes sesiones. También estará contenida información relacionada con futuros proyectos, propuestas de debates...

----------------------------------

## 1. Información de las sesiones

### 1.1 Kickoff (14/04/2026): 

Hemos realizado la primera actividad del club con las siguientes propuestas:

    1. Sesión pública: Dependencia cognitiva de la IA (Lucía)
    buscar ponente de Psicología (Dpto. Personalidad) o Ciencias de la Educación o alternativa

    2. Sesión pública: Oportunidades y amenazas para el sector informático (Cristian)

    3. Sesión pública: Ciberseguridad post-IA (Víctor) intervención de Ale

    4. Sesión pública: Qué nos enseña la IA y límites en tareas creativas (Celia/Víctor)
    intervención de FV / documental AlphaFold

    5. Sesión pública: Ética en el uso de la IA generativa (Hugo) buscar ponente (Víctor Muñoz)

    6. Experimento: Montar un agente IA para gestionar Club de la IA (Cristian/Ale Jiménez) cuenta en Proton+Google > Gemini

    7. Crear un "Manual de uso de la IA" para la escuela / Proponer un curso cero junto con Linux (OpenBokeron)

    8. Crear un repo en GitHub (Francisco) / Imagen (Lucía): README organizativo

    9. Crear servidor en Discord (Javier) / Trello, si procede (FV)

### 1.2 Dependencia cognitiva (23/04/2026):

Hemos realizado el primer debate del club relacionado con la dependencia cognitiva a la IA. Hemos recopilado la siguiente información:

    1. Proyecto educativo: Incluir estudio de deuda cognitiva en el Observatorio. Se propone incorporar este análisis como línea de seguimiento para medir riesgos y evolución en el uso cotidiano de IA.

    2. Proyecto educativo: Entrevistas a desarrolladores senior en empresas malagueñas. Recoger experiencias reales sobre su uso de la IA: más fácil en formato texto y más complejo en videollamada.

    3. Conclusión del debate: La IA como herramienta potencialmente igualitaria puede contribuir a reducir desigualdades si su acceso, formación y uso responsable se fomentan de manera inclusiva.

----------------------------------

## 2. Herramientas y enlaces

### 2.1 Herramienta de publicación de noticias (web)

La web no usa un formulario de subida directa. El bloque **"Hilo de noticias"** carga el archivo `noticias.json`, que se genera automáticamente a partir de los archivos Markdown de la carpeta `noticias/`.

El flujo de publicación es este:

1. Crear una noticia en `noticias/` con nombre `AAAA-MM-DD-slug.md`.
2. Añadir cabecera con metadatos (título, fecha, fuente, etiquetas, etc.).
3. Escribir el cuerpo en Markdown (admite enlaces, negritas/cursivas e imágenes).
4. Hacer commit y push a `main`.
5. GitHub Actions ejecuta `scripts/build.py` y actualiza `noticias.json` + `feed.xml` automáticamente.

Plantilla recomendada para una noticia:

```md
---
title: "Título de la noticia"
date: 2026-04-26
draft: false
url: "https://enlace-a-la-fuente"
source: "Nombre del medio"
tags: [IA, debate, educación]
---

Resumen o comentario de la noticia en Markdown.
```

### 2.2 Repositorio y contribución

Para clonar este repositorio y contribuir en el proyecto:

```
git clone https://github.com/umafoss/clubia.git
```

----------------------------------

