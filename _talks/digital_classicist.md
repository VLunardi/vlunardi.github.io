---
title: "Static and contextual emebddings for tracing semantic change: the case of Christian Latin"
collection: talks
type: "Talk"
permalink: /talks/digital_classicist
venue: "Digital Classicist London 2025"
date: 2025-06-20
location: "Institute of Classical Studies"
excerpt: ''
---
Abstract: \\

In recent decades, a variety of quantitative, statistical, and machine learning tools have been developed to analyse digital corpora. Among these, computational methods for detecting semantic change in diachronic corpora have gained increasing attention (see e.g. Tahmasebi, Borin, and Jatowt 2021). This paper explores how word embeddings can be used to trace semantic change in Latin, with a focus on lexical phenomena driven by the spread of Christianity. 

Latin underwent significant lexical transformation under Christianity’s influence, both due to biblical translations from Greek and the need to introduce new religious concepts. This makes Christian Latin a particularly rich sociolect to examine through these innovative methods.

Building on previous research (Perrone et al. 2021, McGillivray and Nowak 2025), this study employs both static embeddings, which assign a single vector representation per word type, and contextual embeddings, which generate unique representations for each word token based on context. The analysis is conducted on a subset of LatinISE (McGillivray and Kilgarriff 2013), covering texts from
300 span style="font-variant:small-caps;">bce</span> to 600 span style="font-variant:small-caps;">ce</span>. By segmenting the corpus into distinct time frames – one pre-dating Christian Latin texts and one including them – we can detect changes in each word’s vector representation, which in turn signal a possible shift in usage (and potentially in meaning). To extract contextual embeddings, we utilize a fine-tuned version of Latin BERT (Bamman and Burns 2020) trained on our selected corpus for a more tailored evaluation.

The results from these models will be compared against each other and against close-reading analysis for a selected set of lexemes. The goals of this study are: (1) evaluate the comparative strengths of static vs. contextual embeddings, (2) determine the extent to which embedding models align with philological evidence, and (3) contribute to broader discussions on integrating digital approaches in Classics and Historical Linguistics.

References: \\
Bamman, David, and Patrick J. Burns. 2020. “Latin BERT: A Contextual Language Model for Classical Philology.” <i>CoRR</i>
abs/2009.10053. arXiv: 2009.10053.\\
McGillivray, Barbara, and Adam Kilgarriff. 2013. “Tools for historical corpus research, and a corpus of Latin.” In <i>New methods
in historical corpus linguistics</i>, edited by Paul Bennett, Martin Durrell, Silke Scheible, and Richard J. Whitt, 247–
257. Tübingen: Narr.\\
McGillivray, Barbara, and Krzysztof Nowak. 2025. “Tracing the semantic change of socio-political terms from Classical to
early Medieval Latin with computational methods.” In <i>Varietate delectamur: Multifarious Approaches to Synchronic
and Diachronic Variation in Latin. Selected Papers from the 14th International Colloquium on Late and Vulgar Latin
(Ghent, 2022)</i>, edited by Giovanbattista Galdi, Simon Aerts, and Alessandro Papini. Turnhout, Belgium: Brepols.\\
Perrone, Valerio, Simon Hengchen, Marco Palma, Alessandro Vatri, Jim Q. Smith, and Barbara McGillivray. 2021. “Lexical
semantic change for Ancient Greek and Latin.” In <i>Computational approaches to semantic change</i>, edited by Nina
Tahmasebi, Lars Borin, Adam Jatowt, Yang Xu, and Simon Hengchen, 287–310. Berlin: Language Science Press.\\
Tahmasebi, Nina, Lars Borin, and Adam Jatowt. 2021. “Survey of Computational Approaches to Diachronic Conceptual
Change.” In <i>Computational approaches to semantic change</i>, edited by Nina Tahmasebi, Lars Borin, Adam Jatowt, Yang
Xu, and Simon Hengchen, 1–91. Berlin: Language Science Press.