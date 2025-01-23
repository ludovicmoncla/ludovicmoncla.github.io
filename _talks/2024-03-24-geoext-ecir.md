---
title: "GeoEDdA: A Gold Standard Dataset for Geo-semantic Annotation of Diderot & d’Alembert’s Encyclopédie"
collection: talks
type: "Talk"
permalink: /talks/2024-03-24-geoext-ecir
venue: "Second International Workshop on Geographic Information Extraction from Texts (GeoExT)"
date: 2024-03-24
location: "Glasgow, Scotland, UK"
---

Authors: [Ludovic Moncla](https://ludovicmoncla.github.io), [Denis Vigier](http://www.icar.cnrs.fr/membre/dvigier/), [Katherine McDonough](https://www.lancaster.ac.uk/history/about/people/katherine-mcdonough)
<br/>
Abstract: This paper describes the methodology for creating GeoEDdA, a gold standard dataset of geo-semantic annotations from entries in Diderot and d'Alembert's eighteenth-century Encyclopédie. 
Aiming to explore spatial information beyond toponyms identified with the commonly used Named Entity Recognition (NER) task, we test the newer span categorization task as an approach for retrieving complex references to places, generic spatial terms, other entities, and relations. 
We test an active learning method, using the Prodigy web-based tool to iteratively train a machine learning span categorization model. The resulting dataset includes labeled spans from 2,200 paragraphs.
As a preliminary experiment, a custom spaCy spancat model demonstrates strong overall performance, achieving an F-score of 86.42%. Evaluations for each span category reveal strengths in recognizing spatial entities and persons (including nominal entities, named entities and nested entities). 
