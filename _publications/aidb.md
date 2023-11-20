---
title: "AIDB: a Sparsely Materialized Database for Queries using Machine Learning"
collection: publications
permalink: /publication/aidb
paperurl: 'http://academicpages.github.io/files/paper_aidb.pdf'
---

# AIDB: a Sparsely Materialized Database for Queries using Machine Learning

- **Submitted to**: ACM SIGMOD/PODS 2024
- **Authors**: Akash Mittal, Chenghao Mo, Jiahao Fang, Chengsong Zhang, Tengjun Jin, Timothy Dai, Daniel Kang (Primary).

## Abstract
Analysts and scientists are interested in automatically analyzing the semantic contents of unstructured, non-tabular data (videos, images, text, and audio). In order to extract semantic information, analysts have turned to machine learning (ML), which can be used in unstructured data analytics systems. The most common method of using ML in analytics systems is to call them as user-defined functions (UDFs). Unfortunately, UDFs can be difficult for query optimizers to reason over. Furthermore, they can be difficult to implement and unintuitive to application users.

Instead of specifying ML models via UDFs, we instead propose specifying mappings between virtual columns in a structured table, where virtual rows are sparsely materialized via ML models. Querying sparsely materialized tables has unique challenges: even the cardinality of tables is unknown ahead of time, rendering a wide range of standard optimization techniques unusable. We propose novel optimizations for accelerating approximate and exact queries over sparsely materialized tables to address these challenges, providing speedups of up to 2-350×. Users are further able to directly query columns as in standard structured tables, removing the need to reason about opaque UDFs. We implement our techniques in AIDB and deploy them in four real-world datasets. Several of these datasets were constructed with collaborators including law professors studying court cases, showing AIDB’s wide applicability.