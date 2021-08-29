## About
**I**nternational **C**orpus **N**etwork of **A**sian **L**earners of **E**nglish annotated with **A**rgumentative **S**tructure and **S**entence **R**eordering ("ICNALE-AS2R" corpus)

## Description

This language resource is a collection of English learner essays which are excepted from [ICNALE](http://language.sakura.ne.jp/icnale/), based on two criteria: grammatical error free and moderately scored. The corpus consists of 434 essays. The corpus includes two layers of annotation. 

- The first layer is an **argumentative structure annotation**. In the argumentative structure annotation, sentences are first differentiated into argumentative and non-argumentative components; then, relations are established between argumentative components to form a hierarchical structure of the text. We refer the corpus with the first annotation layer as "ICNALE-AS."

- The second layer is a **sentence rearrangement annotation**, which improves text coherence and organisation qualities. Rearrangement may cause irrelevant or incorrect referring and connective expressions. To correct these, text repair also follows after sentence rearrangement annotation, e.g., replacing pronouns with their referents or editing inappropriate connectives, to retain the original meaning of the text. We refer the corpus with the first and second annotation layers as "ICNALE-AS2R."

The annotation was conducted using the [TIARA](https://github.com/wiragotama/TIARA-annotationTool) annotation tool. To visualise the annotation, you may open the essays using the tool, which is available for free at the following site:
[https://wiragotama.github.io/TIARA-annotationTool/](https://github.com/wiragotama/TIARA-annotationTool)

## Citation
Please cite all of the following papers when using the "ICNALE-AS" corpus in your study.

- Shinichiro Ishikawa. 2013. [The ICNALE and Sophisticated Contrastive Interlanguage Analysis of Asian Learners of English](http://www.lib.kobe-u.ac.jp/infolib/meta_pub/G0000003kernel_81006678). In Learner Corpus Studies in Asia and the World, vol 1, pp. 91–118.
- Shinichiro Ishikawa. 2018. [The ICNALE Edited Essays: A Dataset for Analysis of L2 English Learner Essays Based on A New Integrative Viewpoint](http://jaecs.com/jnl/ECS25/ECS25_117-130.pdf). In English Corpus Linguistics, vol 25, pp. 1–14.
- Jan Wira Gotama Putra, Simone Teufel, Takenobu Tokunaga. 2021. [Annotating Argumentative Structure in English-as-foreign-language Learner Essays](https://www.doi.org/10.1017/S1351324921000218). In Natural Language Engineering, pp. 1-27.

If you use the "ICNALE-AS2R" corpus, also cite the following paper on top of those three above.

- Jan Wira Gotama Putra, Simone Teufel, Takenobu Tokunaga. 2021. [Parsing Argumentative Structure in English-as-foreign-language Essays](https://www.aclweb.org/anthology/2021.bea-1.10/). In Proceedings of the Sixteenth Workshop on Innovative Use of NLP for Building Educational Applications, Association for Computational Linguistics, pp. 97-109, April 2021. 

## Corpus Distribution
The corpus is distributed through Gengo-Shigen-Kyokai ("Language Resources Association" in Japan). Please visit [https://www.gsk.or.jp/en/catalog/gsk2021-a](https://www.gsk.or.jp/en/catalog/gsk2021-a).

## Folder Structure
- ```html``` contains the annotated essay in TIARA internal format
- ```tsv (ICNALE-AS)``` contains the essays annotated only with argumentative structure, in ```.tsv``` format
- ```tsv (ICNALE-AS2R)``` contains the essays annotated with two layers of annotation: (1) argumentative structure and (2) sentence reordering followed by text repair. 
- ```essay_list.csv``` contains the list of annotated essays. This is useful for cross-checking
- ```ICNALE-AS2R readme.md``` is this file
- ```annotation_guideline.pdf``` is our annotation guideline
