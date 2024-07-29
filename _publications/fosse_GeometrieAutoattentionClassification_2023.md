---
title: "Géométrie de l'auto-Attention en classification : Quand la géométrie remplace l'attention"
collection: publications
permalink: /publication/fosse_GeometrieAutoattentionClassification_2023
excerpt: #'This paper is about fixing template issue #693.'
date: 05/06/2023
venue: 'Actes de la 30e Conférence sur le Traitement Automatique des Langues Naturelles (TALN), volume 1 : travaux de recherche originaux -- articles longs'
paperurl: 'https://aclanthology.org/2023.jeptalnrecital-long.11.pdf'
citation: 'Loïc Fosse, Duc Hau Nguyen, Pascale Sébillot, and Guillaume Gravier. 2023. Géométrie de l’auto-attention en classification : quand la géométrie remplace l’attention. In Actes de CORIA-TALN 2023. Actes de la 30e Conférence sur le Traitement Automatique des Langues Naturelles (TALN), volume 1 : travaux de recherche originaux -- articles longs, pages 137–150, Paris, France. ATALA.'
---

Abstract (En)
======
Several studies have highlighted the anisotropy of embeddings produced by a BERT model within a sentence, meaning their concentration in a given direction, especially in a classification task. In this article, we seek to better understand this phenomenon and how this convergence is constructed by closely analyzing the geometric properties of embeddings, keys, and values in a self-attention layer. We show that the direction in which the embeddings align characterizes the class membership of the sentence. We then study the intrinsic functioning of the self-attention layer and the mechanisms at play between keys and values to ensure the construction of an anisotropic representation. This construction occurs progressively as multiple layers are stacked. It also proves to be robust to external constraints on the distribution of attention weights, which the model compensates for by adjusting the values and keys.

Résumé (Fr)
======
Plusieurs études ont mis en évidence l’anisotropie des plongements issus d’un modèle BERT au sein d’un énoncé, c’est-à-dire leur concentration dans une direction donnée, notamment dans une tâche de classification. Dans cet article, nous cherchons à mieux comprendre ce phénomène et comment cette convergence se construit en analysant finement les propriétés géométriques des plongements, des clés et des valeurs dans une couche d’auto-attention. Nous montrons que la direction vers laquelle les plongements s’alignent caractérise la classe d’appartenance de l’énoncé. Nous étudions ensuite le fonctionnement intrinsèque de la couche d’auto-attention et les mécanismes en jeu entre clés et valeurs pour garantir la construction d’une représentation anisotrope. Cette construction se fait de manière progressive lorsque plusieurs couches sont empilés. Elle s’avère également robuste à des contraintes externes sur la distribution des poids d’attention, compensées par le modèle en jouant sur les valeurs et les clés.
