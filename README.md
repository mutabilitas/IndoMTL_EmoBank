# IndoMTL_EmoBank

## Overview
This repository contains IndoMTL_EmoBank, an Indonesian version of [EmoBank](https://github.com/JULIELab/EmoBank/) with the sentecnes machine translated using the Microsoft Translator API and the VAD (Valence-Arousal-Dominance) values transferred from the original English-language dataset (specifically `emobank.csv`).

*This dataset was originally constructed as part of the author's undergraduate final year project.*

### ⚠️ Important Disclaimer: IndoMTL_EmoBank is *not accurate* due to both the machine-translated nature of the text used and the naïve transferance of VAD values.

The best practice would be to use verified ENG-ID translation of the EmoBank text and manual annotation using Self-Assessment-Manikin (SAM).

However, due to the scope of the FYP and the lack of a pre-existing sentence-level VAD corpus in Bahasa Indonesia, this method was chosen as per the thesis advisor's guidance. It has been identified as a resource gap in Bahasa Indonesia/Indonesian NLP Research.

Word-level Indonesian VAD corpus exist:
* As part of **CEFI**: *Concreteness, Emotion, and Subjective frequency norms for Indonesian words* (public dataset [available](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5138238/))
* **IVAW**: *Indonesian Valence and Arousal Words* (public dataset [not available](https://ieeexplore.ieee.org/document/8674370/))

## References
* Sven Buechel and Udo Hahn. 2017. EmoBank: Studying the Impact of Annotation Perspective and Representation Format on Dimensional Emotion Analysis. In EACL 2017 - Proceedings of the 15th Conference of the European Chapter of the Association for Computational Linguistics. Valencia, Spain, April 3-7, 2017. Volume 2, Short Papers, pages 578-585. Available: http://aclweb.org/anthology/E17-2092
