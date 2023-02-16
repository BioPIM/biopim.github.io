---
layout: about
title: Home
permalink: /
subtitle: 

profile:
  align: right
  image: # biopim_toplogo.png
  image_circular: false # crops the image to make it circular
  address: # >
    # <p>555 your office number</p>
    # <p>123 your address street</p>
    # <p>Your City, State 12345</p>

news: false  # includes a list of news items
tweets: true
selected_papers: true # includes a list of papers marked as "selected={true}"
social: true  # includes social icons at the bottom of the page
---

# About

**BioPIM** project aims to leverage the emerging processing-in-memory (PIM) technologies to enable powerful edge computing. We will focus on co-designing algorithms and data structures commonly used in bioinformatics together with several types of PIM architectures to obtain the highest benefit in cost, energy, and time savings. BioPIM will also impact other fields that employ similar algorithms. Our designs and algorithms will not be limited to cheap hardware, and they will impact computation efficiency on all forms of computing environments including cloud platforms.

The vision of **BioPIM** is the realization of cheap, ultra-fast and ultra-low energy mobile genomics that eliminates the current dependence of sequence analysis on large and power-hungry computing clusters/data-centers.

The targeted breakthrough of **BioPIM** is to invent and leverage in-memory computing architectures to fundamentally improve the performance and energy efficiency of various important bioinformatics algorithms to make mobile genomics a reality, focusing on 

* in-memory alignment and search,
* in-memory global and local genome assembly, 
* in-memory pangenome analysis, and 
* in-memory variation calling and base calling.

# Objectives

* **Objective 1:** Optimizing data structures and algorithms commonly used in genomics for in-memory computing. These data structures include de Bruijn and string graphs, Bloom filters, Counting Quotient Filters (CQF), Burrows-Wheeler Transformation (BWT), and FM-index. Our redesigns will also include algorithms for the operations supported by each data structure. Algorithms will include both combinatorial (alignment, search, pangenomics), and machine learning / deep learning-based methodologies (variation calling, basecalling).
* **Objective 2:**  Hardware/software co-development of common bioinformatics algorithms used in genomics for in-memory architectures, such as global and local alignment, text-pattern search, approximate pattern search (i.e., read mapping), graph traversal, and using graphs for assembly and pangenome analysis. This aim will include both PIM architecture design and PIM-enabled software development.
* **Objective 3:** PIM prototypes and software development that employ the designed architecture.
