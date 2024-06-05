---
layout: post
title: Database performance tuning with Multi-armed Bandits
subtitle: Performance tuning is a crucial step in database preparation since it enables fast query responses to user enquiries. This project aims to fully automate performance tuning of databases by choosing physical design structures that speed up query analysis. Our approach removes the need for costly human personnel and automatically adjusts to user queries (and data) whilst they are doing analysis. DBA Bandits are not only able to successfully tune unpredictable and ad hoc workloads (unknown a priori), but also provide statistical guarantees on the fitness of proposed design structures – first such guarantees in the world of database performance tuning.
author: Renata
categories: MAB
banner:
  # video: https://vjs.zencdn.net/v/oceans.mp4
  loop: true
  volume: 0.8
  start_at: 8.5
#   image: https://miro.medium.com/v2/resize:fit:1200/1*5q0Mihf29fftuXpKWWX2uA.png
  image: /assets/images/bandit.png
  opacity: 0.618
  background: "#000"
  height: "100vh"
  min_height: "38vh"
  heading_style: "font-size: 4.25em; font-weight: bold; text-decoration: underline"
  subheading_style: "color: gold"
tags: MAB index tunning
top: 1
sidebar: []
---

Performance tuning is a crucial step in database preparation since it enables fast query responses to user enquiries. This project aims to fully automate performance tuning of databases by choosing physical design structures that speed up query analysis. Our approach removes the need for costly human personnel and automatically adjusts to user queries (and data) whilst they are doing analysis. DBA Bandits are not only able to successfully tune unpredictable and ad hoc workloads (unknown a priori), but also provide statistical guarantees on the fitness of proposed design structures – first such guarantees in the world of database performance tuning.

### 1. No DBA? No regret! Multi-armed bandits for index tuning of analytical and HTAP workloads with provable guarantees

<p><b>TKDE, 2023. No DBA? No regret! Multi-armed bandits for index tuning of analytical and HTAP workloads with provable guarantees. M. Perera, B. Oetomo, B. I. P. Rubinstein, and <u>R. Borovica-Gajic</u>. <a href="/data/2023_tkde.pdf" target="_blank">PDF</a>&nbsp;<a href="https://ieeexplore.ieee.org/abstract/document/10113193" target="_blank">Link</a>&nbsp;<a href="https://dblp.org/rec/journals/tkde/PereraORB23.html?view=bibtex" target="_blank">BibTex</a></b></p>

### 2. Cutting to the Chase with Warm-Start Contextual Bandits

<p><b>KAIS, 2023. Cutting to the Chase with Warm-Start Contextual Bandits. B. Oetomo, M. Perera, <u>R. Borovica-Gajic</u> and B. I. P. Rubinstein. <a href="/data/2023_kais.pdf" target="_blank">PDF</a>&nbsp;<a href="https://link.springer.com/article/10.1007/s10115-023-01861-2" target="_blank">Link</a>&nbsp;<a href="https://dblp.org/rec/journals/kais/OetomoPBR23.html?view=bibtex" target="_blank">BibTex</a></b></p> 

### 3. HMAB: Self-Driving Hierarchy of Bandits for Integrated Physical Database Design Tuning

<p><b>VLDB, 2022. HMAB: Self-Driving Hierarchy of Bandits for Integrated Physical Database Design Tuning. M. Perera, B. Oetomo, B. I. P. Rubinstein, and <u>R. Borovica-Gajic</u>. <a href="/data/2022_vldb.pdf" target="_blank">PDF</a>&nbsp;<a href="/data/2022_vldb_slides.pdf" target="_blank">Slides</a>&nbsp;<a href="https://www.vldb.org/pvldb/vol16/p216-perera.pdf" target="_blank">Link</a>&nbsp;<a href="https://www.youtube.com/watch?v=98xl-A9ZSOs" target="_blank">Video</a>&nbsp;<a href="https://dblp.org/rec/journals/pvldb/PereraORB22.html?view=bibtex" target="_blank">BibTex</a>&nbsp;<a href="https://github.com/malingaperera/HMAB" target="_blank">Code</a></b></p> 

<div style="display: flex; justify-content: center;">
    <iframe width="80%" height="400" src="https://www.youtube.com/embed/98xl-A9ZSOs" frameborder="0" allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

### 4. Cutting to the Chase with Warm-Start Contextual Bandits

<p><b>ICDM, 2021. Cutting to the Chase with Warm-Start Contextual Bandits. B. Oetomo, M. Perera, <u>R. Borovica-Gajic</u> and B. I. P. Rubinstein. <a href="/data/2021_icdm.pdf" target="_blank">PDF</a>&nbsp;<a href="/data/2021_icdm_slides.pdf" target="_blank">Slides</a>&nbsp;<a href="https://ieeexplore.ieee.org/document/9679034" target="_blank">Link</a>&nbsp;<a href="/data/2021_icdm.mp4" target="_blank">Video</a>&nbsp;<a href="https://dblp.org/rec/conf/icdm/OetomoPBR21.html?view=bibtex" target="_blank">BibTex</a></b></p> 

<div style="display: flex; justify-content: center;">
    <iframe width="80%" height="400" src="https://renata.borovica-gajic.com/data/videos/2021_icdm.mp4" frameborder="0" allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

### 5. DBA bandits: Self-driving index tuning under ad-hoc, analytical workloads with safety guarantees

<p><b>ICDE, 2021. DBA bandits: Self-driving index tuning under ad-hoc, analytical workloads with safety guarantees. M. Perera, B. Oetomo, B. I. P. Rubinstein, and <u>R. Borovica-Gajic</u>. <a href="/data/2021_icde.pdf" target="_blank">PDF</a>&nbsp;<a href="/data/2021_icde_slides.pdf" target="_blank">Slides</a>&nbsp;<a href="https://ieeexplore.ieee.org/document/9458699" target="_blank">Link</a>&nbsp;<a href="https://www.youtube.com/watch?v=7PohjU29Hjk" target="_blank">Video</a>&nbsp;<a href="https://dblp.uni-trier.de/rec/conf/icde/PereraORB21.html?view=bibtex" target="_blank">BibTex</a>&nbsp;<a href="https://github.com/malingaperera/DBABandits" target="_blank">Code</a></b></p> 

<div style="display: flex; justify-content: center;">
    <iframe width="80%" height="400" src="https://www.youtube.com/embed/7PohjU29Hjk" frameborder="0" allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

