---
title: Redes de Co-expresión Genética
summary: Construcción y análisis de redes de co-expresión genética utilizando diferentes algoritmos
tags:
  - GCN
date: '2019-11-01T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Gene Co-expression Networks of U. maydis
  focal_point: Smart



# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: GCN
---

La expresión genética es uno de los procesos más conservados e importantes de los organismos vivos. Este proceso permite transcribir y traducir la información almacenada en el ADN a productos funcionales como las proteínas.
La expresión genética se ha medido a escala genómica por medio de microarreglos y de la secuenciación de ARN. A lo largo de los años esta información se ha almacenado en bases de datos especializadas como GEO y SRA del NCBI, las cuales en los últimos años han tenido un aumento considerable en la cantidad de datos disponible.
Por otro lado, recientes aproximaciones han mostrado que las propiedades subyacentes de los organismos solo pueden ser explicadas al estudiarlos como sistemas complejos, de manera que una perspectiva de redes ha sido planteada para estudiar las relaciones biológicas de un organismo a diferentes niveles.
En particular, las redes de co-expresión genética tienden a tomar una gran relevancia en los últimos años debido al incremento de la información experimental generada de las técnicas de microarreglos y RNAseq, en estas redes cada nodo representa a un gene y la arista o interacción es la relación entre cada par de nodos debido a un valor significativo de co-expresión entre de ellos. Estas redes permiten identificar patrones o módulos de genes que se co-expresan y que pueden tener una función biológica similar, además estos módulos pueden estar relacionados con funciones biológicas de interés industrial, médico y académico.
En los últimos años los algoritmos de aprendizaje automático han tenido un gran crecimiento debido a la aplicabilidad en diferentes tipos de datos estructurados, además este tipo de algoritmos pueden generalizar y predecir nuevos datos. La aplicación de estos algoritmos se ha expandido a áreas como la Biológica, en el cual permiten identificar nuevos blancos de fármacos, identificar promotores de genes o factores de transcripción. 
Nosotros buscamos procesar esta información para identificar estas redes de co-expression genética utilizando diferentes métodos como WGCNA y algoritmos genéticos acoplados a biclustering. Los cuales son aplicados a diferentes conjuntos de datos que incluyen bacterias, hongos y tipos de cáncer, con el objetivo de identificar conjuntos de genes importantes.
