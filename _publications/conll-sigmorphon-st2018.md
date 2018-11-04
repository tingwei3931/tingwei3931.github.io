---
title: "IIT(BHU)–IIITH at CoNLL–SIGMORPHON 2018 Shared Task on Universal Morphological Reinflection"
collection: publications
permalink: /publication/conll-sigmorphon-st2018
excerpt: 'System Description Paper for IIT(BHU)–IIITH system at [CoNLL–SIGMORPHON 2018 Shared Task on Universal Morphological Reinflection](https://sigmorphon.github.io/sharedtasks/2018/)'
date: 2018-10-30
venue: 'Proceedings of the CoNLL SIGMORPHON 2018 Shared Task: Universal Morphological Reinflection'
paperurl: 'http://www.aclweb.org/anthology/K18-3013'
citation: 'Abhishek Sharma, Ganesh Katrapati and Dipti Misra Sharma. IIT(BHU)–IIITH at CoNLL–SIGMORPHON 2018 Shared Task on Universal Morphological Reinflection. In Proceedings of the CoNLL SIGMORPHON 2018 Shared Task: Universal Morphological Reinflection, Brussels. Association for Computational Linguistics'
---

# Abstract

This paper describes the systems submitted by IIT (BHU), Varanasi/IIIT Hyderabad (IITBHU–IIITH) for Task 1 of CoNLL–SIGMORPHON 2018 Shared Task on Universal Morphological Reinflection (Cotterell et al., 2018). The task is to generate the inflected form given a lemma and set of morphological features. The systems are evaluated on over 100 distinct languages and three different resource settings (low, medium and high). We formulate the task as a sequence to sequence learning problem. As most of the characters in inflected form are copied from the lemma, we use Pointer-Generator Network (See et al., 2017) which makes it easier for the system to copy characters from the lemma. Pointer-Generator Network also helps in dealing with out-of-vocabulary characters during inference. Our best performing system stood 4th among 28 systems, 3rd among 23 systems and 4th among 23 systems for the low, medium and high resource setting respectively.