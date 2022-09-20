---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Conekt Bioenergy"
summary: ""
authors: [renato-augusto-correa-dos-santos,diego-mauricio-riano-pachon,fvperes,jmmunozp,asocardoso]
tags: [transcriptomics, co-expression networks, expression profiles]
categories: []
date: 2022-09-13T15:58:37-03:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

Open platforms for data mining democritize the access to analyses that would only be achieved by scientists with computer science skills. CoNekT is a platform for analysis of expression profiles and co-expression networks that can be used to study one or more conditions or tissues in an organism, and the comparative analysis among different organisms. Since CoNekT is open source, research groups with particular interests can populate an instance for mining transcriptome data and raise hypotheses in their field of expertise in biology. Our research group studies plants of interest in bioenergy. Recently, we implemented an instance of CoNekT entitled "CoNekT Bioenergy" for analysis of plants with publicly available RNA-Seq data, particularly grasses with C3 and C4 metabolism. This instance was implemented in the cloud service "USP Internuvem", using the Apache2 web service and MariaDB/Mysql as the database management system. We selected plants with C4 metabolism in genera _Setaria_, _Sorghum_, _Pennisetum_, _Panicum_, _Miscanthus_, _Paspalum_, _Digitaria_, and sugarcane, and with C3 metabolism, including _Bracrypodium distachyon_ and _Nicotiana tabacum_, for prospection of RNA-Seq datasets. For selection of publicly avaiable sequencing runs, we recovered NCBI metadata using Python scripts connected to an sqlite3 database (with the Python3 built-in connector), and the Biopython module Entrez, which recovers NCBI information such as SRA, Biosample, and Bioproject metadata. The following criteria were used to download sequencing data: short "bulk" RNA-Seq reads, "paired-end" layout, experiments with an associated publication indexed in PubMed, and "strand-specific" sequencing. Since "strandness" information is not available for most datasets, we used Salmon to infer is. So far, we have downloaded sequencing data for leaf experiments of _Setaria viridis_ (C4 model) and for two different organs (leaves and flowers) in _Nicotiana tabacum_ (C3). For these two species, we used 130 and four datasets, respectively, for quantification of transcript expression and generation of a TPM matrix, followed by inference of a co-expression network with LSTrAP. CDS were downloaded  either from Phytozome-JGI (_S. viridis_) and SolGenomics (_N. tabacum_), and functional annotation was obtained from the same databases or carried out with InterProScan. Next steps in this work include functional annotation, selection of additional datasets, generation of expression profiles and co-expression networks for the remaining species. Next steps in this work also involve using tools for processing natural language to better exploit NCBI metadata. We will also study the expression of specific genes and conservation of co-expression modules in plants of our interest, assign plant ontology terms that facilitate the organization of datasets analysed by users of our platform, include new species and implement new functionalities.


