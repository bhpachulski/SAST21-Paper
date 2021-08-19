# [On the use of test smells for prediction of flaky tests](https://localhost)

[![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa] [![DOI](https://zenodo.org/badge/397793628.svg)](https://zenodo.org/badge/latestdoi/397793628)

Bruno Henrique Pachulski Camara <sup>1</sup>, <sup>2</sup>, <br />
Marco Aure ́lio Graciotto Silva <sup>3</sup>, <br />
Andre T. Endo <sup>4</sup>, <br />
Silvia Regina Vergilio <sup>2</sup>. <br />

<sup>1</sup> Centro Universitário Integrado, Campo Mourão, PR, Brazil <br />
<sup>2</sup> Department of Computer Science, Federal University of Parana ́, Curitiba, PR, Brazil <br />
&nbsp; &nbsp; &nbsp; bhpachulski@ufpr.br, silvia@inf.ufpr.br <br />
<sup>3</sup> Department of Computing, Federal University of Technology - Parana ́, Campo Mourão, PR, Brazil <br />
&nbsp; &nbsp; &nbsp; magsilva@utfpr.edu.br <br />
<sup>4</sup> Department of Computing, Federal University of Technology - Parana ́, Cornélio Procópio, PR, Brazil <br />
&nbsp; &nbsp; &nbsp; andreendo@utfpr.edu.br <br />

This paper has been submitted for publication in *SAST 2021 - VI Simpósio Brasileiro de Teste de Software Sistemático e Automatizado*.

This experimental package is organized by aproaches, semlls and vocabulary-based. For each of the questions, some files can be executed to obtain the data that are presented in the paper.

## Abstract

> Regression testing is an important phase to deliver software with quality. However, flaky tests hamper the evaluation of test results and can increase costs. This is because a flaky test may pass or fail non-deterministically and to identify properly the flakiness of a test requires rerunning the test suite multiple times. To cope with this challenge, approaches have been proposed based on prediction models and machine learning. Existing approaches based on the use of the test case vocabulary may be context-sensitive and prone to overfitting, presenting low performance when executed in a cross-project scenario. To overcome these limitations, we investigate the use of test smells as predictors of flaky tests. We conducted an empirical study to understand if test smells have good performance as a classifier to predict the flakiness in the cross-project context, and analysed the information gain of each test smell. We also compared the test smell-based approach with the vocabulary-based one. As a result, we obtained a classifier that had a reasonable performance (Random Forest, 0.83\%) to predict the flakiness in the testing phase. This classifier presented better performance than vocabulary-based model for  cross-project prediction. The "Assertion Roulette" and "Sleepy Test" test smell types are the ones associated with the best information gain values.

Keywords: test flakiness, regression testing, replication studies, machine learning

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg