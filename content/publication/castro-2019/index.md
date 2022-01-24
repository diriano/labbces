---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Gene regulatory networks on transfer entropy (GRNTE): a novel approach to
  reconstruct gene regulatory interactions applied to a case study for the plant pathogen
  Phytophthora infestans.'
subtitle: ''
summary: ''
authors:
- Juan Camilo Castro
- Ivan Valdés
- Laura Natalia Gonzalez-García
- Giovanna Danies
- Silvia Cañas
- Flavia Vischi Winck
- Carlos Eduardo Ñústez
- Silvia Restrepo
- Diego Mauricio Riaño-Pachón
tags:
- '"*Algorithms"'
- '"*Databases"'
- '"Genetic"'
- '"Entropy"'
- '"Gene Regulatory Networks/*genetics"'
- '"*Models"'
- '"Theoretical"'
- '"Phytophthora infestans/*genetics"'
- '"*Biological networks"'
- '"*Entropy"'
- '"*Gene regulation"'
- '"*Information theory"'
- '"*Transcription factors"'
categories: []
date: '2019-04-01'
lastmod: 2021-11-03T00:16:16-03:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2021-11-04T01:47:50.836546Z'
publication_types:
- '2'
abstract: "BACKGROUND: The increasing amounts of genomics data have helped in the\
  \ understanding of the molecular dynamics of complex systems such as plant and animal\
  \ diseases. However, transcriptional regulation, although playing a central role\
  \ in the decision-making process of cellular systems, is still poorly understood.\
  \ In this study, we linked expression data with mathematical models to infer gene\
  \ regulatory networks (GRN). We present a simple yet effective method to estimate\
  \ transcription factors' GRNs from transcriptional data. METHOD: We defined interactions\
  \ between pairs of genes (edges in the GRN) as the partial mutual information between\
  \ these genes that takes into account time and possible lags in time from one gene\
  \ in relation to another. We call this method Gene Regulatory Networks on Transfer\
  \ Entropy (GRNTE) and it corresponds to Granger causality for Gaussian variables\
  \ in an autoregressive model. To evaluate the reconstruction accuracy of our method,\
  \ we generated several sub-networks from the GRN of the eukaryotic yeast model,\
  \ Saccharomyces cerevisae. Then, we applied this method using experimental data\
  \ of the plant pathogen Phytophthora infestans. We evaluated the transcriptional\
  \ expression levels of 48 transcription factors of P. infestans during its interaction\
  \ with one moderately resistant and one susceptible cultivar of yellow potato (Solanum\
  \ tuberosum group Phureja), using RT-qPCR. With these data, we reconstructed the\
  \ regulatory network of P. infestans during its interaction with these hosts. RESULTS:\
  \ We first evaluated the performance of our method, based on the transfer entropy\
  \ (GRNTE), on eukaryotic datasets from the GRNs of the yeast S. cerevisae. Results\
  \ suggest that GRNTE is comparable with the state-of-the-art methods when the parameters\
  \ for edge detection are properly tuned. In the case of P. infestans, most of the\
  \ genes considered in this study, showed a significant change in expression from\
  \ the onset of the interaction (0 h post inoculum - hpi) to the later time-points\
  \ post inoculation. Hierarchical clustering of the expression data discriminated\
  \ two distinct periods during the infection: from 12 to 36 hpi and from 48 to 72\
  \ hpi for both the moderately resistant and susceptible cultivars. These distinct\
  \ periods could be associated with two phases of the life cycle of the pathogen\
  \ when infecting the host plant: the biotrophic and necrotrophic phases. CONCLUSIONS:\
  \ Here we presented an algorithmic solution to the problem of network reconstruction\
  \ in time series data. This analytical perspective makes use of the dynamic nature\
  \ of time series data as it relates to intrinsically dynamic processes such as transcription\
  \ regulation, were multiple elements of the cell (e.g., transcription factors) act\
  \ simultaneously and change over time. We applied the algorithm to study the regulatory\
  \ network of P. infestans during its interaction with two hosts which differ in\
  \ their level of resistance to the pathogen. Although the gene expression analysis\
  \ did not show differences between the two hosts, the results of the GRN analyses\
  \ evidenced rewiring of the genes' interactions according to the resistance level\
  \ of the host. This suggests that different regulatory processes are activated in\
  \ response to different environmental cues. Applications of our methodology showed\
  \ that it could reliably predict where to place edges in the transcriptional networks\
  \ and sub-networks. The experimental approach used here can help provide insights\
  \ on the biological role of these interactions on complex processes such as pathogenicity.\
  \ The code used is available at https://github.com/jccastrog/GRNTE under GNU general\
  \ public license 3.0."
publication: '*Theoretical biology & medical modelling*'
---
