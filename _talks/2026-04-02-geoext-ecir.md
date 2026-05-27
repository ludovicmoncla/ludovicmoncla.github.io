---
title: "Automatic Construction of a Geo-Historical Knowledge Graph from Early Modern Encyclopedic Texts"
collection: talks
type: "Talk"
permalink: /talks/2026-04-02-geoext-ecir
venue: "Fourth International Workshop on Geographic Information Extraction from Texts (GeoExT)"
date: 2026-04-02
location: "Delft, Netherlands"
---

Authors: Bin Yang, [Ludovic Moncla](https://ludovicmoncla.github.io), Fabien Duchateau, Frédérique Laforest
<br/>
Abstract: Early modern encyclopedias, such as Diderot and d’Alembert’s (1751–1772), offer a valuable resource for studying
the evolution of geographical knowledge, yet their sheer scale complicates manual analysis. This paper presents
an automated method for constructing a geo-historical knowledge graph from these texts. We propose spatial
and provenance ontologies tailored to the corpus and introduce a gold standard of 2,750 geographical articles.
The pipeline combines supervised learning and Large Language Models (LLMs) for article classification, entity
typing, and spatial relation extraction. Performance reaches F1 = 92% for relations and F1 > 97% for classification,
resulting in an RDF graph of 35,000 entities and 46,000 relations. This work paves the way for the computational
analysis of early geographical knowledge. Data, models, and code are available on HuggingFace and Gitlab.
