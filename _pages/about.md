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
tweets: false
selected_papers: true # includes a list of papers marked as "selected={true}"
social: true  # includes social icons at the bottom of the page
---

# About

**The BioPIM project ended on October 31, 2026. The project website is kept online to share our results with the community.**

**BioPIM** project aimed to leverage the emerging processing-in-memory (PIM) technologies to enable powerful edge computing. We focused on co-designing algorithms and data structures commonly used in bioinformatics together with several types of PIM architectures to obtain the highest benefit in cost, energy, and time savings. BioPIM also impacted other fields that employ similar algorithms. Our designs and algorithms were not limited to cheap hardware, and they impacted computation efficiency on all forms of computing environments including cloud platforms.

The vision of **BioPIM** was the realization of cheap, ultra-fast and ultra-low energy mobile genomics to eliminate the dependence of sequence analysis on large and power-hungry computing clusters/data-centers.

The targeted breakthrough of **BioPIM** was to invent and leverage in-memory computing architectures to fundamentally improve the performance and energy efficiency of various important bioinformatics algorithms to make mobile genomics a reality, focusing on 

* in-memory alignment and search,
* in-memory global and local genome assembly, 
* in-memory pangenome analysis, and 
* in-memory variation calling and base calling.


# Objectives

* **Objective 1:** Optimizing data structures and algorithms commonly used in genomics for in-memory computing. These data structures included de Bruijn and string graphs, Bloom filters, Counting Quotient Filters (CQF), Burrows-Wheeler Transformation (BWT), and FM-index. Our redesigns also included algorithms for the operations supported by each data structure. Algorithms included both combinatorial (alignment, search, pangenomics), and machine learning / deep learning-based methodologies (variation calling, basecalling).
* **Objective 2:**  Hardware/software co-development of common bioinformatics algorithms used in genomics for in-memory architectures, such as global and local alignment, text-pattern search, approximate pattern search (i.e., read mapping), graph traversal, and using graphs for assembly and pangenome analysis. This aim included both PIM architecture design and PIM-enabled software development.
* **Objective 3:** PIM prototypes and software development that employed the designed architecture.
