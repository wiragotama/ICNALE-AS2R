## About
**I**nternational **C**orpus **N**etwork of **A**sian **L**earners of **E**nglish (ICNALE) annotated with **A**rgumentative **S**tructure and **S**entence **R**eordering (AS2R)

## Description
The ICNALE-AS2R corpus consists of 434 argumentative essays written by college students from various Asian countries (sampled from the [ICNALE](http://language.sakura.ne.jp/icnale/) corpus). The corpus includes two layers of annotation. 

- The first layer is an **argumentative structure annotation**. In the argumentative structure annotation, sentences are first differentiated into argumentative and non-argumentative components; then, relations are established between argumentative components to form a hierarchical structure of the text. We refer the corpus with the first annotation layer as `ICNALE-AS'.

- The second layer is a **sentence rearrangement annotation**, which improves text coherence and organisation qualities. Rearrangement may cause irrelevant or incorrect referring and connective expressions. To correct these, text repair also follows after sentence rearrangement annotation, e.g., replacing pronouns with their referents or editing inappropriate connectives, to retain the original meaning of the text. We refer the corpus with the first and second annotation layers as `ICNALE-AS2R'.

The annotation was conducted using the [TIARA](https://github.com/wiragotama/TIARA-annotationTool) annotation tool. To visualise the annotation, you may open the essays using the tool, which is available for free at the following site:
[https://wiragotama.github.io/TIARA-annotationTool/](https://github.com/wiragotama/TIARA-annotationTool)

## Citation
Please cite all of the following papers when using the 'ICNALE-AS' corpus in your study.

- Shinichiro Ishikawa. 2013. The ICNALE and Sophisticated Contrastive Interlanguage Analysis of Asian Learners of English. In Learner Corpus Studies in Asia and the World, vol 1, pp. 91–118.
- Shinichiro Ishikawa. 2018. The ICNALE Edited Essays: A Dataset for Analysis of L2 English Learner Essays Based on A New Integrative Viewpoint. In English Corpus Linguistics, vol 25, pp. 1–14.
- Jan Wira Gotama Putra, Simone Teufel, Takenobu Tokunaga. 2021. Annotating Argumentative Structure in English-as-foreign-language Learner Essays. In Natural Language Engineering Journal, (vol): no, pp. XX-YY [*in press*].

If you use the 'ICNALE-AS2R' corpus, also cite the following paper.

- Jan Wira Gotama Putra, Simone Teufel, Takenobu Tokunaga. 2021. Parsing Argumentative Structure in English-as-foreign-language Essays. In Proceedings of the Sixteenth Workshop on Innovative Use of NLP for Building Educational Applications, pp. XX-YY. 

## Download Link
The corpus will be distributed through Gengo-Shigen-Kyokai ("Language Resources Association" in Japan, [https://www.gsk.or.jp/en/](https://www.gsk.or.jp/en/)). We are currently working to process the distribution **[link to be provided]**. 

## Folder Structure
- ```html``` contains the annotated essay in TIARA internal format
- ```tsv (ICNALE-AS)``` contains the essays annotated only with argumentative structure, in ```.tsv``` format
- ```tsv (ICNALE-AS2R)``` contains the essays annotated with two layers of annotation: (1) argumentative structure and (2) sentence reordering followed by text repair. 
- ```essay_list.csv``` contains the list of annotated essays. This is useful for cross-checking
- ```ICNALE-AS2R readme.md``` is this file
- ```annotation_guideline.pdf``` is our annotation guideline
