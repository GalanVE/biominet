---
title: 'Predicting bacterial transcription factor binding sites through machine learning and structural characterization based on DNA duplex stability'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - André Borges Farias
  - Gustavo Sganzerla Martinez
  - admin
  - Marisa Fabiana Nicolás
  - Ernesto Pérez-Rueda
  

date: '2024-11-14T00:00:00Z'
doi: 'https://doi.org/10.1093/bib/bbae581'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-11-14T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: Briefings in Bioinformatics
publication_short: Briefings in Bioinformatics

abstract: 'Transcriptional factors (TFs) in bacteria play a crucial role in gene regulation by binding to specific DNA sequences, thereby assisting in the activation or repression of genes. Despite their central role, deciphering shape recognition of bacterial TFs-DNA interactions remains an intricate challenge. A deeper understanding of DNA secondary structures could greatly enhance our knowledge of how TFs recognize and interact with DNA, thereby elucidating their biological function. In this study, we employed machine learning algorithms to predict transcription factor binding sites (TFBS) and classify them as directed-repeat (DR) or inverted-repeat (IR). To accomplish this, we divided the set of TFBS nucleotide sequences by size, ranging from 8 to 20 base pairs, and converted them into thermodynamic data known as DNA duplex stability (DDS). Our results demonstrate that the Random Forest algorithm accurately predicts TFBS with an average accuracy of over 82% and effectively distinguishes between IR and DR with an accuracy of 89%. Interestingly, upon converting the base pairs of several TFBS-IR into DDS values, we observed a symmetric profile typical of the palindromic structure associated with these architectures. This study presents a novel TFBS prediction model based on a DDS characteristic that may indicate how respective proteins interact with base pairs, thus providing insights into molecular mechanisms underlying bacterial TFs-DNA interaction.'

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [machine learning, transcription factor binding site, DNA duplex stability]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: '../Borges2024.pdf'
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
  caption: ' Schematic illustrating the workflow for acquiring, training, validating, and interpreting the predictive model designed to TFBS '
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

