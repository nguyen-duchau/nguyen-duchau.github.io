---
title: "Géométrie de l'auto-Attention en classification : Quand la géométrie remplace l'attention"
collection: publications
permalink: /publication/fosse_EtudeStatistiquePlongements_2022
excerpt: #'This paper is about fixing template issue #693.'
date: 27/06/2022
venue: '[JEP/TALN/RECITAL](https://aclanthology.org/venues/jeptalnrecital/)'
paperurl: 'https://aclanthology.org/2022.jeptalnrecital-taln.24.pdf'
citation: 'Loïc Fosse, Duc-Hau Nguyen, Pascale Sébillot, and Guillaume Gravier. 2022. Une étude statistique des plongements dans les modèles transformers pour le français (An empirical statistical study of embeddings in French transformers). In Actes de la 29e Conférence sur le Traitement Automatique des Langues Naturelles. Volume 1 : conférence principale, pages 247–256, Avignon, France. ATALA.'
---

Abstract (En)
======
We study the statistical properties of embeddings in transformer models for French. We rely on an analysis of variance, intra-sentence cosine similarities, and the effective rank of embeddings at different levels of a transformer, for both pre-trained models and models adapted for text classification. We show that the pre-trained FlauBERT and CamemBERT models exhibit very different behaviors, even though both tend to generate anisotropic representations, i.e., concentrating in a cone within the embedding space, as observed for English. Adaptation to text classification alters the models' behavior, particularly in the final layers, and strongly promotes alignment of the embeddings, also reducing the effective dimensionality of the space in the end. We also highlight a link between the convergence of embeddings within a sentence and text classification, a link whose nature remains challenging to grasp.

Résumé (Fr)
======
Nous étudions les propriétés statistiques des plongements dans les modèles transformers pour le français. Nous nous appuyons sur une analyse de la variance, des similarités cosinus intra-phrase et du rang effectif des plongements aux différents niveaux d’un transformer, pour des modèles pré-entraînés et des modèles adaptés à la classification de textes. Nous montrons que les modèles FlauBERT et CamemBERT pré-entraînés ont des comportements très différents même si les deux ont une tendance à générer des représentations anisotropiques, c’est-à-dire se concentrant dans un cône au sein de l’espace des plongements, comme observé pour l’anglais. L’adaptation à la classification de textes modifie le comportement des modèles, notamment dans les dernières couches, et procure une tendance forte à l’alignement des plongements, réduisant également la dimension effective de l’espace au final. Nous mettons également en évidence un lien entre convergence des plongements au sein d’une phrase et classification de texte, lien dont la nature reste difficile à appréhender.