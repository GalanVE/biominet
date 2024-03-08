---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: hero
    demo: True # Only display this section in the Hugo Blox Builder demo site
    content:
      title: DBNL
      image:
        filename: hero-academic.png
      cta:
        label: '**Get Started**'
        url: https://hugoblox.com/templates/
      cta_alt:
        label: Ask a question
        url: https://discord.gg/z8wNYzb
      cta_note:
        label: >-
          <div style="text-shadow: none;"><a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star Hugo Blox Builder</a></div><div style="text-shadow: none;"><a class="github-button" href="https://github.com/HugoBlox/theme-academic-cv" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star the Academic template</a></div>
      text: |-
        **Generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 500,000+ sites.**

        **Easily build anything with blocks - no-code required!**

        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.

        <!--Custom spacing-->
        <div class="mb-3"></div>
        <!--GitHub Button JS-->
        <script async defer src="https://buttons.github.io/buttons.js"></script>
    design:
      background:
        gradient_end: '#1976d2'
        gradient_start: '#004ba0'
        text_color_light: true

  - block: collection
    id: about
    content:
      title: Data mining, Bioinformatics and Networks Laboratory
      subtitle: ''
      text: 'DBN Lab is located at the Instituto de Investigaciones en Matemáticas Aplicadas y en Sistemas at the Universidad Nacional Autónoma de México.

        The primary research focus of the laboratory is to study biological phenomena from a complex systems perspective. For this, we use different data mining strategies to obtain, preprocess and build data sets, which provide the basis for identifying and building networks. These include Gene Regulatory Networks, Gene Co-expression Networks, Drug and target networks, among others.'
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      # Choose how many columns the section has. Valid values: 1 or 2.
      columns: '1'

  - block: collection
    id: posts
    content:
      title: Blog
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - post
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '2'

  - block: portfolio
    id: projects
    content:
      title: Projects
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
      title: Recent Publications
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

  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact


  - block: about.biography
    id: team
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin

  - block: skills
    content:
      title: Skills
      text: ''
      # Choose a user to display skills from (a folder name within `content/authors/`)
      username: admin
    design:
      columns: '1'

  - block: collection
    content:
      title: Team
      text: |-
        <p><strong>Postdoctoral researcher</strong></p>

        - <b>Francisco Javier Luna Leal</b>. Aplicación de la teoría de redes al proceso de construcción del conocimiento en la modernidad temprana: el caso de los vínculos sociales de Johannes Kepler. 

        <p><strong>PhD students</strong></p> 

        - <b>Raúl Galindo Hernández</b>. Identificación de patrones en datos de co-expresión de genes utilizando modelos de aprendizaje automático. Posgrado en ciencias e ingeniería de la computatión, IIMAS - UNAM. En curso.

        <p><strong>Undergraduate students</strong></p>

        - <b>Luis Mario Paz Villagarcia</b>. Análisis de la red de co-expresión genética de <i>Entamoeba histolytica</i>. Licenciatura en Biología. FES Zaragoza UNAM. En curso.

        - <b>Eduardo Alexis Valencia Dorantes</b>.   Dinámica de circuitos de regulación genética de <i>Mycoobacterium tuberculosis</i>. Licenciatura en Matemáticas Aplicadas. Facultad de Ciencias UNAM. En curso.

        - <b>Alfredo Castillo Jiménez</b>. Identificación de patrones de expresión en <i>Ustilago maydis</i> por medio de redes de co-expresión. Licenciatura en Biología, Facultad de Ciencias - UNAM. En curso.

        <p><strong>Social service students</strong></p>

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

        - <b>Edgar Ivan Lozada Sánchez</b>. Minería de datos aplicada a sistemas biológicos. Matemáticas Aplicadas y computación. 2023.

      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      

  - block: tag_cloud
    content:
      title: Popular Topics
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
      title: Contact
      subtitle:
      email: edgardo.galan@iimas.unam.mx

      address:
        street: Circuito Escolar
        city: Ciudad Universitaria
        region: Ciudad de México
        postcode: '04510'
        country: México
        country_code: MX
      directions: Third level, office 304.
      office_hours:
        - 'Monday 09:00 to 16:30'
        - 'Tuesday 09:00 to 16:30'
        - 'Wednesday 09:00 to 16:30'
        - 'Thursday 09:00 to 16:30'
        - 'Friday 09:00 to 16:30'
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      coordinates:
        latitude: '19.33027'
        longitude: '-99.18066'  
      # Automatically link email and phone or display as text?
      autolink: true

    design:
      columns: '2'
---