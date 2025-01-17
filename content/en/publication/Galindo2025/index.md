---
title: 'Online-adjusted evolutionary biclustering algorithm to identify significant modules in gene expression data'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Raúl Galindo-Hernández
  - Katya Rodríguez-Vázquez
  - admin
  - Carlos Ignacio Hernández Castellanos

date: '2025-01-02T00:00:00Z'
doi: 'https://doi.org/10.1093/bib/bbae681'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-01-02T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: Briefings in Bioinformatics
publication_short: Brief Bioinform

abstract: 'Analyzing gene expression data helps the identification of significant biological relationships in genes. With a growing number of open biological datasets available, it is paramount to use reliable and innovative methods to perform in-depth analyses of biological data and ensure that informed decisions are made based on accurate information. Evolutionary algorithms have been successful in the analysis of biological datasets. However, there is still room for improvement, and further analysis should be conducted. In this work, we propose Online-Adjusted EVOlutionary Biclustering algorithm (OAEVOB), a novel evolutionary-based biclustering algorithm that efficiently handles vast gene expression data. OAEVOB incorporates an online-adjustment feature that efficiently identifies significant groups by updating the mutation probability and crossover parameters. We utilize measurements such as Pearson correlation, distance correlation, biweight midcorrelation, and mutual information to assess the similarity of genes in the biclusters. Algorithms in the specialized literature do not address generalization to diverse gene expression sources. Therefore, to evaluate OAEVOB’s performance, we analyzed six gene expression datasets obtained from diverse sequencing data sources, specifically Deoxyribonucleic Acid microarray, Ribonucleic Acid (RNA) sequencing, and single-cell RNA sequencing, which are subject to a thorough examination. OAEVOB identified significant broad gene expression biclusters with correlations greater than  across all similarity measurements employed. Additionally, when biclusters are evaluated by functional enrichment analysis, they exhibit biological functions, suggesting that OAEVOB effectively identifies biclusters with specific cancer and tissue-related genes in the analyzed datasets. We compared the OAEVOB’s performance with state-of-the-art methods and outperformed them showing robustness to noise, overlapping, sequencing data sources, and gene coverage.'

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [biclustering, evolutionary algorithm, gene expression data, RNA-sequencing, single-cell RNA-sequencing, machine learning]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: '../Galindo2025.pdf'
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
  caption: ' The main steps of OAEVOB for all the generations '
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

