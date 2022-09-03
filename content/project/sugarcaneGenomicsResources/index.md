---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Sugarcane Genomics and Transcriptomics Resources"
summary: ""
authors: [diego-mauricio-riano-pachon,fvperes,jmmunozp, vrossi]
tags: [transcriptomics, pan-transcriptome, sugarcane, genomics, SP80-3280]
categories: []
date: 2022-08-28T15:29:30-03:00

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

Sugarcane is a widely cultivated plant within Poaceae, which fixates CO2 via C4 photosynthesis. Sugarcane is one of the most important crops around the world, as it is the main source for common sugar, bioenergy and other bioproducts. Modern sugarcane cultivars are the result of classical breeding approaches thar involved interspecific crosses between members of the complex Saccharum. Their genomes are among the most complex in crops. These hybrids are polyploid, highly polymorphic and can present aneuploidy. Recent developments in sequencing technologies are allowing accessing Sugarcane genetic information on a genome-wide level. In Brazil, two research groups used long read sequencing technologies to read the genome information for the hybrid SP80-3280, to a shallow level, here we present a comparison of these two genome versions and a comprehensive gene set for this cultivar. Besides the Brazilian cultivar, there is a French, and a Colombian cultivar with genome sequences available, as well as genomic information for some of the parental species. However, there are many studies accessing the transcriptome of diverse cultivars from around the world. Despite of this, these transcriptomics data cannot easily be exploited due to the lack of a commonly accepted reference. We have exploited publicly available transcriptomics data for 48 cultivars from around the world to create a sugarcane pan-transcriptome. In total we detected over five million protein-coding transcripts, that can be clustered into similarity groups, representing genes and closely related paralogues. We were able to identify approximately twelve thousand groups of transcripts that tend to appear in all cultivars, that we call core set. We show that we can attribute a probable origin for most of these transcripts (S. spontaneum, S. officinarum or S. barbieri).  We are making this resource available to the public, and we are developing a platform to ease mining of these data.

{{< figure src="posterCBFV_2022.png" caption="Poster presented at the XVIII Brazilian Congress of Plant Physiology" numbered="false" width=250 >}}

{{% staticref "uploads/posterCBFV_2022.pdf" "newtab" %}}Poster PDF{{% /staticref %}}



# Data availability

[Transcriptome assemblies (FASTA)](https://figshare.com/articles/dataset/Genotype_specific_transcriptome_assemblies_-_Fasta_files/18623039): 48 genotype-specific transcriptome assemblies exploiting public RNA-Seq data.

[Quality of our 48 transcriptome assemblies](https://figshare.com/articles/dataset/Genotype_specific_transcriptome_assemblies_-_Evaluation_metrics/18623321): Genotype-specific transcriptome evaluation generated with BUSCO, Transrate and Salmon.

[CDS (FASTA)](https://figshare.com/articles/dataset/Genotype_specific_CDS_-_Fasta_files/19426715): CDS files from our 48 genotype-specific transcriptome assemblies.

[PEP (FASTA)](https://figshare.com/articles/dataset/Genotype_specific_PEP_-_Fasta_files/19426721): PEP files from our 48 genotype-specific transcriptome assemblies (Over than 5.2e6 protein-coding transcripts).

[Local BLAST server (temp)](http://200.144.245.42:4567): Temporarily available BLAST server to query our transcriptome assemblies. 
