---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Infraestructure"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2023-11-16T23:04:24-02:00
lastmod: 2023-11-16T23:04:24-02:00
featured: false
draft: false
comments: false  
# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

## Computational Infraestructure

Our primary scientific instrument is a small bioinformatics cluster, acquired through resources from CAPES, FINEP, and FAPESP. The cluster currently includes the following components:

- Lenovo ThinkSystem DS2200 storage with 72TB capacity
- Dell with (2) Intel® Xeon® Silver 4310 processors - 48 threads, (8) 64GB RAM modules, (2) 960GB SSDs, and (6) 2TB HDDs
- Dell with (2) Intel® Xeon® CPU E5-2660 processors - 56 threads, 512GB RAM, and (2) 100GB HDDs

Unfortunately, one of the components failed last year (2023) due to electrical outages:

- HP with (2) processors - 24 threads, 256GB RAM, (2) 100GB HDDs, and (2) 2TB HDDs

Our bioinformatics cluster is available to all researchers at CENA/USP. The conditions for use are as follows:

- The required computations must be performed using software compatible with the Linux operating system.
- Interested users must request access to the cluster and complete training on the use of the job queueing system, Son of Grid Engine (SGE).

[SGE (Son of Grid Engine)](https://gridengine.sourceforge.io/SGE/) is a powerful job scheduler that manages and optimizes the distribution of computational tasks across the cluster's resources. It ensures efficient use of computational power and fair access for all users. 

External users may be granted access to this infrastructure on a case-by-case basis. If interested please get in [contact](/contact/).

For those interested in using this infraestructure, we recomend getting familiar with basic linux, using the following materials:

- [The Unix Shell](https://swcarpentry.github.io/shell-novice/)
- Part 1 and 2 of  [Unix And Shell Primer for Biologist](http://korflab.ucdavis.edu/Unix_and_Perl/current.html)
- [Command-line Bootcamp](http://korflab.ucdavis.edu/bootcamp.html)

We also have prepared a tutorial for the use of SGE in our cluster:

- {{% staticref "uploads/BioinfoClusterCENAUSP.pdf" %}}Bioinformatics Cluster @ CENA/USP{{% /staticref %}}

Once you have been granted access to the cluster and have completed the training, you can submit your jobs using the SGE commands. You jobs will be automatically scheduled and executed by the cluster. [Here](qstatCluster.html) you can see the current load of the cluster.

Additionally, we have an application server with the following components:

- Dell with (2) Intel® Xeon® Silver 4316 processors - 80 threads, (2) 32GB RAM modules, and (5) 2TB HDDs
Dell EMC ME5012 storage with 56TB capacity

The following is a photo of out bioinformatics cluster:

![Bioinfo Cluster](LabBCES_BioinfoCluster.jpg)

## Dry Lab

We have a dry lab equipped with workstations featuring small desktop computers (Intel Core i3/i5, 16GB - 32 GB RAM, 250 GB SSD e 1TB HD). We hold regular group meetings every week, with part of the team joining online through a 50-inch TV.

![Bioinfo Dry Lab](LabBCES_DryLab.jpg)
