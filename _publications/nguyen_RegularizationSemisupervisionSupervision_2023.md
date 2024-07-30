---
title: "Regularization, Semi-supervision, and Supervision for a Plausible Attention-Based Explanation"
collection: publications
permalink: /publication/nguyen_RegularizationSemisupervisionSupervision_2023
excerpt: #'This paper is about the number 1. The number 2 is left for future work.'
date: 19-06-2023
venue: '28th International Conference on Applications of Natural Language to Information Systems (NLDB) 2023'
slidesurl: #'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://hal.science/hal-04132646v1/document'
citation: 'Duc Hau Nguyen, Cyrielle Mallart, Guillaume Gravier & Pascale Sébillot. Regularization, Semi-supervision, and Supervision for a Plausible Attention-Based Explanation. In Natural Language Processing and Information Systems (NLDB), pp. 285–298, 2023.'
---

Abstract
======
Attention mechanism is contributing to the majority of recent advances in machine learning for natural language processing. Additionally, it results in an attention map that shows the proportional influence of each input in its decision. Empirical studies postulate that attention maps can be provided as an explanation for model output. However, it is still questionable to ask whether this explanation helps regular people to understand and accept the model output (the plausibility of the explanation). Recent studies show that attention weights in RNN encoders are hardly plausible because they spread on input tokens. We thus propose three additional constraints to the learning objective function to improve the plausibility of the attention map: regularization to increase the attention weight sparsity, semi-supervision to supervise the map by a heuristic and supervision by human annotation. Results show that all techniques can improve the attention map plausibility at some level. We also observe that specific instructions for human annotation might have a negative effect on classification performance. Beyond the attention map, results on text classification tasks also show that the contextualization layer plays a crucial role in finding the right space for finding plausible tokens, no matter how constraints bring the gain.