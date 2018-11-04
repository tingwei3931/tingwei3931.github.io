---
title: "CoNLL-SIGMORPHON Shared Task on Morphological Inflection"
excerpt: "CoNLL-SIGMORPHON Shared Task on Morphological Inflection"
collection: projects
---

During my internship at IIIT Hyderabad in summer of 2018, I worked on the CoNLL shared task on Universal Morphological Inflection. The task was to generate the inflected form given a lemma and a set of morphological features. We formulated this task as sequence and sequence learning problem with the string of characters as the sequence. We explored ways to condition the output sequence on the set of morphological features, including encoding the tags using LSTM, using attention and combining the attention context vectors of the lemma and the features using Hierarchical Attention. As most of the characters in the inflected form are copied from the lemma, we added an explicit copy mechanism (Pointer-Generator Network) to facilitate copying. This proved very useful for the low resource setting of the task and gave high gains. All in all, our team was among the top 3 teams for all the tracks of the shared task.