---
# Leave the homepage title empty to use the site title
title:
date: 2025-03-05
type: landing

sections:
  - block: hero
    content:
      title: |
        <span style="font-size: 2rem; text-align: center;">Datos Biológicos y Redes Complejas</span>
      image:
        filename: Logo.png
      text: |
        <br>

        <p style="font-size: 0.9rem; line-height: 1.4; text-align: justify;">
        El Grupo de Datos Biológicos y Redes Complejas forma parte del Departamento de Ingeniería de Sistemas Computacionales y Automatización en el Instituto de Investigaciones en Matemáticas Aplicadas y en Sistemas (IIMAS) de la Universidad Nacional Autónoma de México (UNAM), ubicado en la Ciudad de México.
        </p>

        <p style="font-size: 0.9rem; line-height: 1.4; text-align: justify;">
        Nuestro grupo trabaja en la Línea de investigación de Ciencia de datos aplicada a Bioinformática y Biología de Sistemas con el objetivo de comprender cómo las interacciones a nivel de la expresión genética permiten a los organismos responder de manera coordinada a estímulos intra y extracelulares desde una perspectiva de sistemas.
        </p>

        <p style="font-size: 0.9rem; line-height: 1.4; text-align: justify;">
        Este enfoque nos ha permitido identificar patrones de genes y proteínas claves en diversos procesos biológicos, como la muerte celular programada de hongos, genes de virulencia de hongos y bacterias, genes relacionados a enfermedades como cáncer de mama y próstata, genes conservados en la regulación y metabolismo, así como el impacto de los fármacos y genes blancos, entre otros.
        </p>

        <p style="font-size: 0.9rem; line-height: 1.4; text-align: justify;">
        Por otro lado, también nos interesa comprender la estructura de redes sociales subyacentes que se reportan en textos históricos, por medio de procesamiento de textos con NLP y análisis de redes complejas por medio de teoría de grafos.
        </p>


  - block: collection
    content:
      title: Proyectos
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen


  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Conoce al equipo →" %}}
    design:
      columns: '1'
---
