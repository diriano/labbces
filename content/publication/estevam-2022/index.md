---
# Documentation: https://wowchemy.com/docs/managing-content/

title: CoCoView - A codon conservation viewer via sequence logos.
subtitle: ''
summary: ''
authors:
- Beatriz Rodrigues Estevam
- Diego Mauricio Riaño-Pachón
tags:
- Codons representation; Consensus sequence; Conserved patterns; Information theory
categories: []
date: '2022-01-01'
lastmod: 2022-08-30T10:17:15-03:00
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
publishDate: '2022-08-30T13:21:58.949046Z'
publication_types:
- '2'
abstract: Sequence logos are a simple way to display a set of aligned sequences, and
  they are useful to identify conserved patterns. Since their introduction, several
  tools have been developed for generating these representations at the single residue
  level (amino acids or nucleotides). We have developed a tool to build sequence logos
  of protein-coding sequences at the codon level, allowing more accurate analysis
  of coding-sequences as they represent synonymous and non-synonymous changes instead
  of showing only changes that imply on amino acid substitutions. We built CoCoView
  on top of the Logomaker Python API. It creates codon sequence logos from a multiple
  sequence alignment of protein-coding sequences. Some properties of the data and
  the generated logos can be controlled by the end-users, such as data redundancy,
  plot type and alphabet color. • Split aligned sequences into codon positions; •
  For each position compute codon frequency and information content; • Use the computed
  information to plot the graphic.
publication: '*MethodsX*'
doi: 10.1016/j.mex.2022.101803
---
