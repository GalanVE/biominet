---
# Leave the homepage title empty to use the site title
title: ''
date: 2025-02-05
type: landing

sections:

  - block: collection
    id: about
    content:
      title: Datos Biológicos y Redes Complejas
      subtitle: 'Bioinformática, Minería de datos y Redes'
      text: |-
          El Grupo de Datos Biológicos y Redes Complejas forma parte del Departamento de Ingeniería de Sistemas Computacionales y Automatización en el Instituto de Investigaciones en Matemáticas Aplicadas y en Sistemas (IIMAS) de la Universidad Nacional Autónoma de México (UNAM), ubicado en la Ciudad de México.

          Nuestro grupo trabaja en la Línea de investigación de Ciencia de datos aplicada a Bioinformática y Biología de Sistemas con el objetivo de comprender como las interacciones a nivel de la expresión genética, permiten a los organismos responden de manera coordinada a estímulos intra y extra celulares desde una perspectiva de sistemas. Este enfoque nos ha permitido identificar patrones de genes y proteínas claves en diversos procesos Biológicos, como la muerte celular programada de hongos, genes de virulencia de hongos y bacterias, genes relacionados a enfermedades como cáncer de mama y próstata, genes conservados en la regulatorio y metabólico, así como el impacto de los fármacos y genes blancos, entre otros. Para alcanzar estos objetivos, hemos desarrollado estrategias en Bioinformática, Minería de Datos, Redes Complejas y Aprendizaje Automático, permitiendo el análisis de datos de expresión genética y genómica a gran escala y la construcción de modelos que contribuyen al entendimiento de la regulación génica en distintos organismos.

           Por otro lado, también nos interesa comprender la estructura de redes sociales subyacentes que se reportan en textos históricos, por medio de procesamiento de textos con NLP y análisis de redes complejas por medio de teoría de grafos.


      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      # Choose how many columns the section has. Valid values: 1 or 2.
      columns: '1'

  #- block: collection
  #  id: posts
  #  content:
  #    title: Blog
  #    subtitle: ''
  #    text: ''
  #    # Choose how many pages you would like to display (0 = all pages)
  #    count: 5
  #    # Filter on criteria
  #    filters:
  #      folders:
  #        - post
  #      author: ""
  #      category: ""
  #      tag: ""
  #      exclude_featured: false
  #      exclude_future: false
  #      exclude_past: false
  #      publication_type: ""
  #    # Choose how many pages you would like to offset by
  #    offset: 0
  #    # Page order: descending (desc) or ascending (asc) date.
  #    order: desc
  #  design:
  #    # Choose a layout view
  #    view: compact
  #    columns: '2'

  - block: portfolio
    id: projects
    content:
      title: Proyectos
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: GRN
          tag: GRN
        - name: GCN
          tag: GCN
        - name: Data mining
          tag: Datamining
        - name: Other
          tag: Other
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      view: Compact
      # For Showcase view, flip alternate rows?
      flip_alt_rows: False

  - block: collection
    id: publications
    content:
      title: Publicaciones recientes
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '2'
      view: citation

  #- block: collection
  #  id: featured
  #  content:
  #    title: Featured Publications
  #    filters:
  #      folders:
  #        - publication
  #      featured_only: true
  #  design:
  #    columns: '2'
  #    view: card

  #- block: collection
  #  id: talks
  #  content:
  #    title: Recent & Upcoming Talks
  #    filters:
  #      folders:
  #        - event
  #  design:
  #    columns: '2'
  #    view: compact


  - block: about.biography
    id: team
    content:
      title: Bibliografía
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin

#  - block: skills
#    content:
#      title: Skills
#      text: ''
      # Choose a user to display skills from (a folder name within `content/authors/`)
#      username: admin
#    design:
#      columns: '1'

  - block: collection
    content:
      title: Equipo
      text: |-
        <p><strong>Investigadores Posdoctorales</strong></p>

        - <b>Dr. Francisco Javier Luna Leal</b> 

          Aplicación de la teoría de redes al proceso de construcción del conocimiento en la modernidad temprana: el caso de los vínculos sociales de Johannes Kepler. 

        - <b>Dr. José Martín Mijangos Tovar</b> 

          Análisis topológico y geométrico de datos en redes complejas.

        <p><strong>Estudiantes de doctorado</strong></p> 

        - <b>MsC. Raúl Galindo Hernández</b> 

          Identificación de patrones en datos de co-expresión de genes utilizando modelos de aprendizaje automático. Posgrado en ciencias e ingeniería de la computatión, IIMAS - UNAM.

        <p><strong>Estudiantes de licenciatura</strong></p>

        - <b>Luis Mario Paz Villagarcia</b> 

          Análisis de la red de co-expresión genética de <i>Entamoeba histolytica</i>. Licenciatura en Biología. FES Zaragoza UNAM. 

        - <b>Eduardo Alexis Valencia Dorantes</b>

          Dinámica de circuitos de regulación genética de <i>Mycoobacterium tuberculosis</i>. Licenciatura en Matemáticas Aplicadas. Facultad de Ciencias UNAM.

        - <b>Gloria Cruz Vásquez</b>

          Análisis de la red de co-expresión del gusano cogollero. Universidad Abierta y a Distancia de México.

        - <b>Rodman Kinkaid Salavarria Hunter</b>

          Estudio de las interacciones entre fármacos y blancos a partir de redes multicapa. Universidad Abierta y a Distancia de México.


        <p><strong>Estudiantes de servicio social</strong></p>

        - <b>Martin Reyes Bolaños</b>. Minería de datos aplicada a sistemas biológicos. Licenciatura en Ingeniería en Computación. UNAM. 2020.

        - <b>Alfredo Castillo Jiménez</b>. Minería de datos aplicada a sistemas biológicos. Licenciatura en Biología. UNAM. 2021.

        - <b>Alan Lozada</b>. Minería de datos aplicada a sistemas biológicos. Matemáticas Aplicadas. UNAM. 2021.

        - <b>Fernando Morales Mendoza</b>. Minería de datos aplicada a sistemas biológicos. Ingeniería en Computación. UNAM. 2022.

        - <b>Juan Ángel López García</b>. Minería de datos aplicada a sistemas biológicos. Ingeniería en Computación. UNAM. 2022.

        - <b>José Juan Hernández Villegas</b>. Minería de datos aplicada a sistemas biológicos. Matemáticas Aplicadas y Computación. UNAM. 2022.

        - <b>Mauricio Díaz Martínez</b>. Minería de datos aplicada a sistemas biológicos. Licenciatura en Matemáticas Aplicadas. UNAM. 2022.

        - <b>William Brandom Estrada Tepec</b>. Minería de datos aplicada a sistemas biológicos. Ingeniería en Computación. UNAM. 2022.

        - <b>Itzel Paola Benítez Trejo</b>. Minería de datos aplicada a sistemas biológicos. Licenciatura en Biología. 2023.

        - <b>Edgar Samuel Palacios Crispín</b>. Desarrollo web para minería de datos biológicos. Licenciatura en Ciencias de la Computación. 2023.

        - <b>Raymundo Méndez García</b>. Desarrollo web para minería de datos biológicos. Licenciatura en Ciencias de la Computación. 2023

        - <b>Sebastián Mendivil Pindter</b>. Minería de datos aplicada a sistemas biológicos.. Licenciatura en Biología. 2023.

        - <b>Edgar Ivan Lozada Sánchez</b>. Minería de datos aplicada a sistemas biológicos. 
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'



  - block: tag_cloud
    content:
      title: Topicos populares
    design:
      columns: '2'
  #- block: markdown
  #  content:
  #    title: Gallery
  #    subtitle: ''
  #    text: |-
  #      {{< gallery album="demo" >}}
  #  design:
  #    columns: '1'

  - block: contact
    id: contact
    content:
      title: Contacto
      subtitle:
      email: edgardo.galan@iimas.unam.mx

      address:
        street: Circuito Escolar
        city: Ciudad Universitaria
        region: Ciudad de México
        postcode: '04510'
        country: México
        country_code: MX
      directions: Edificio A, nivel 3, oficina 304.
      office_hours:
        - 'Lunes a Viernes de 09:00 a 16:30'

      # Choose a map provider in `params.yaml` to show a map from these coordinates
      coordinates:
        latitude: '19.33027'
        longitude: '-99.18066'  
      # Automatically link email and phone or display as text?
      autolink: true

    design:
      columns: '2'
---
