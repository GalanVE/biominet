---
# Leave the homepage title empty to use the site title
title:
date: 2025-03-05
type: landing

sections:
  - block: hero
    content:
      title: |
        <span style="font-size: 2rem; text-align: center;">Ciencia de Datos Biológicos y Redes Complejas</span>
      image:
        filename: Logo.png
      text: |
        <br>

        <p style="font-size: 0.9rem; line-height: 1.4; text-align: justify;">
        El Grupo deCiencia de Datos Biológicos y Redes Complejas forma parte del Departamento de Ingeniería de Sistemas Computacionales y Automatización del Instituto de Investigaciones en Matemáticas Aplicadas y en Sistemas (IIMAS) de la Universidad Nacional Autónoma de México (UNAM), en la Ciudad de México.
        </p>

        <p style="font-size: 0.9rem; line-height: 1.4; text-align: justify;">
        Nuestro trabajo se sitúa en la intersección entre la biología, la ciencia de datos, el aprendizaje automático y el estudio de grafos. Nos enfocamos en el análisis de datos biológicos masivos y en la modelación de sistemas complejos, con el objetivo de comprender cómo las interacciones a nivel de la expresión genética permiten a los organismos responder de manera coordinada a estímulos intra y extracelulares desde una perspectiva de sistemas.
        </p>

        <p style="font-size: 0.9rem; line-height: 1.4; text-align: justify;">
        Este enfoque nos ha permitido identificar patrones relevantes en genes y proteínas asociados a diversos procesos biológicos, como la muerte celular programada en hongos, la virulencia en bacterias y hongos, enfermedades como el cáncer de mama y próstata, así como mecanismos conservados en regulación y metabolismo. Adicionalmente, hemos desarrollado nuevos algoritmos que nos permiten identificar y clasificar estas entidades biológicas. Asimismo, estudiamos el efecto de fármacos y la identificación de posibles genes blanco.
        </p>

        <p style="font-size: 0.9rem; line-height: 1.4; text-align: justify;">
        De manera complementaria, desarrollamos investigación en el análisis de redes complejas a partir de datos no biológicos, particularmente en el estudio de redes sociales extraídas de textos históricos mediante técnicas de procesamiento de lenguaje natural y teoría de grafos.
        </p>

        <p style="font-size: 0.9rem; line-height: 1.4; text-align: justify;">
        Además de la investigación, el grupo tiene como objetivo central la formación de estudiantes en ciencia de datos aplicada a problemas biológicos reales. Promovemos una visión interdisciplinaria, fomentando la autonomía en el manejo de datos, la programación científica, el diseño de algoritmos y el pensamiento crítico para la validación e interpretación de resultados.
        </p>
        <p style="font-size: 0.9rem; line-height: 1.4; text-align: justify;">
        El trabajo dentro del grupo se basa en la colaboración, la discusión crítica y la participación activa en todas las etapas del proceso de investigación, desde la formulación de preguntas hasta la comunicación de resultados en informes, tesis y publicaciones científicas.
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
          filename: Grupo.png
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
        {{% cta cta_link="./people/" cta_text="Conoce al grupo →" %}}
    design:
      columns: '1'
---
