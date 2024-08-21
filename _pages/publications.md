---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## AIDB: a Sparsely Materialized Database for Queries using Machine Learning

- Tengjun Jin, Akash Mittal, Chenghao Mo, Jiahao Fang, Chengsong Zhang, Timothy Dai, Daniel Kang.
- DEEM '24: Proceedings of the Eighth Workshop on Data Management for End-to-End Machine Learning,
  Pages 23-28.
- [DOI: 10.1145/3650203.3663329](https://doi.org/10.1145/3650203.3663329)

### Abstract
Analysts and scientists are interested in automatically analyzing the semantic contents of unstructured, non-tabular data (videos, images, text, and audio). These analysts have turned to unstructured data systems leveraging machine learning (ML). The most common method of using ML in analytics systems is to call them as user-defined functions (UDFs). Unfortunately, UDFs can be difficult for query optimizers to reason over. Furthermore, they can be difficult to implement and unintuitive to application users.

Instead of specifying ML models via UDFs, we propose specifying mappings between virtual columns in a structured table, where virtual rows are sparsely materialized via ML models. Querying sparsely materialized tables has unique challenges: even the cardinality of tables is unknown ahead of time, rendering a wide range of standard optimization techniques unusable. We propose novel optimizations for accelerating approximate and exact queries over sparsely materialized tables to address these challenges, providing up to 350x cheaper queries. We implement our techniques in AIDB and deploy them in four real-world datasets. Several of these datasets were constructed with collaborators including law professors studying court cases, showing AIDB's wide applicability.