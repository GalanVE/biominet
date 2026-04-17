---
title: 'A methodological framework for the use of AI tools in automated workflows for generating validated and structured historical datasets'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - José Antonio Motilla-Chávez
  - Diego Espitia
  - Diego Perez-Martinez
  - admin
  - Edgardo Ugalde
  - Marcela Lomelí-Jasso
  - Eduardo Perez-Martinez
  - Hector G. Perez-Gonzalez
  - Fernando Carlín-Loza
  - Valeria Martínez-Ramírez
  - Martín Zumaya Hernández


date: '2026-01-17T00:00:00Z'
doi: 'https://doi.org/10.1007/s42803-026-00121-3'

# Schedule page publish date (NOT publication's date).
publishDate: '2026-01-17T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: International Journal of Digital Humanities 
publication_short: Int J Digit Humanities 

abstract: 'The growing availability of digitized historical collections has enabled large-scale computational research; however, transforming heterogeneous and noisy textual data into structured and analyzable formats remains a major challenge within the Digital Humanities. This article presents a reproducible workflow for historical text processing that integrates Optical Character Recognition (OCR), Large Language Models (LLM)-assisted post-correction, and Named Entity Recognition (NER) into a unified pipeline. Implemented within the n8n automation framework, the workflow emphasizes transparency, modularity, and human-in-the-loop validation, enabling scholars to maintain interpretive control over data transformation. The pipeline is evaluated on five historical corpora in Spanish (eighteenth and nineteenth centuries), demonstrating significant reductions in Character and Word Error Rates (up to -93.5% and -66.8% respectively) through lightweight, open-weight LLMs (Gemma 3 27B, Qwen 2.5 32B, LLaMA 3 70B). NER performance using FLAIR achieves F1 scores above 0.96 for persons and organizations, and a semantic-level similarity evaluation is added through CoNES to assess distributed lexical recovery. Beyond reporting benchmarks, the study reflects on the epistemic implications of automated processing in historical research and argues that reproducible data pipelines are essential infrastructures for scaling relational analyses such as co-entity networks and computational historiography. All results contribute toward a transparent methodological model that bridges humanistic inquiry and computational automation while preserving scholarly traceability.'

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [machine learning, data processing, IA, complex networks]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ' Schematic overview of the automated workflow for OCR processing, LLM-assisted correction, and entity extraction, implemented through the n8n orchestration framework'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - Datascience


---

