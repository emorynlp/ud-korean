# Universal Dependencies in Korean

The Universal Dependencies in Korean (UDK) project provides dependency treebanks pseudo-annotated by the guidelines from the [Universal Dependencies](http://universaldependencies.org) framework.
Thus far, UDK has generated universal dependency trees for the following corpora:

* [Google Treebank](google): 6,339 sentences, 80,392 tokens (McDonald et al., 2013).
* [Kaist Treebank](kaist): 27,363 sentences, 350,090 tokens (Choi et al., 1994).
* [Penn Treebank](penn): 5,010 sentences, 132,041 tokens (Han et al., 2002).


## Citation

This work is a collaborative effort between Emory University, University of Pittsburgh, and Institute for Human & Machine Cognition.

* [Building Universal Dependency Treebanks in Korean](doc/lrec-2018.pdf), Jayeol Chun, Na-Rae Han, Jena D. Hwang, and Jinho D. Choi. In Proceedings of the 11th International Conference on Language Resources and Evaluation, LREC'18, Miyazaki, Japan, 2018.


## References

* [Universal Dependency Annotation for Multilingual Parsing](https://www.aclweb.org/anthology/P13-2017), Ryan McDonald, Joakim Nivre, Yvonne Quirmbach-Brundage, Yoav Goldberg, Dipanjan Das, Kuzman Ganchev, Keith Hall, Slav Petrov, Hao Zhang, Oscar Täckström, Claudia Bedini, Núria Bertomeu Castelló, Jungmee Lee. In Proceedings of the 51st Annual Meeting of the Association for Computational Linguistics, ACL'13, Sofia, Bulgaria, 2013.
* [Penn Korean Treebank: Development and Evaluation](http://www.aclweb.org/anthology/Y02-1007), Chung-hye Han, Na-Rae Han, Eon-Suk Ko, Martha Palmer, Heejong Yi. In Proceedings of the 16th Pacic Asia Conference on Language, Information and Computation, PACLIC'02, Jeju, Korea, 2002.
* [KAIST Tree Bank Project for Korean: Present and Future Development](doc/kaist.pdf). Key-Sun Choi, Young S. Han, Young G. Han, and Oh W. Kwon. In Proceedings of the International Workshop on Sharable Natural Language Resources, Nara, Japan, 1994.



## Contact

* [Jinho D. Choi](http://www.mathcs.emory.edu/~choi)


## Part-of-Speech Tags

| Tag   | Google |   Kaist |    Penn |
|:-----:|-------:|--------:|--------:|
|  ADJ  |  2,760 |  14,223 |   3,431 |
|  ADP  |  1,791 |   1,498 |   1,251 |
|  ADV  | 11,361 |  49,204 |  15,174 |
|  AUX  |     74 |  12,906 |   2,263 |
| CCONJ |    223 |  19,368 |   2,453 |
|  DET  |    573 |   4,824 |     685 |
|  INTJ |      3 |      56 |       0 |
|  NOUN | 32,345 | 105,193 |  46,866 |
|  NUM  |    847 |   4,848 |   7,931 |
|  PART |     31 |     268 |     464 |
|  PRON |    682 |   7,712 |     857 |
| PROPN |    490 |  12,366 |  12,257 |
| PUNCT | 10,440 |  38,925 |  13,428 |
| SCONJ |      0 |  18,466 |   9,780 |
|  SYM  |    328 |     260 |     376 |
|  VERB | 18,431 |  59,273 |  13,855 |
|   X   |     13 |     700 |     970 |
| **Total** | **80,392** | **350,090** | **132,041** |


## Dependency Labels

|    Label   | Google |   Kaist |    Penn |
|:----------:|-------:|--------:|--------:|
|     acl    |      4 |  21,468 |   1,488 |
|  acl:relcl |  3,194 |       0 |       0 |
|    advcl   |  4,515 |  20,487 |  11,636 |
|   advmod   |  8,810 |  19,102 |   2,964 |
|    amod    |  1,566 |  16,584 |   1,595 |
|    appos   |  1,544 |   1,059 |   1,182 |
|     aux    |     64 |  18,935 |   4,807 |
|    case    |  1,624 |   1,343 |   1,548 |
|     cc     |    223 |   5,234 |     785 |
|    ccomp   |    651 |  15,655 |   9,858 |
|     clf    |      0 |       1 |       0 |
|  compound  |      0 |  24,696 |  28,908 |
|    conj    |  3,863 |  20,774 |   9,960 |
|     cop    |    102 |     303 |     418 |
|    csubj   |     21 |   1,202 |   8,014 |
|     dep    |  2,437 |   3,019 |     609 |
|     det    |    569 |   4,824 |     685 |
|  det:poss  |  2,508 |       0 |       0 |
|  discourse |      0 |      47 |       0 |
| dislocated |      0 |  20,964 |       0 |
|    fixed   |     13 |   3,186 |     528 |
|    flat    | 12,252 |     803 |      18 |
|    iobj    |    108 |     967 |     222 |
|    mark    |    372 |     799 |   1,003 |
|    nmod    |  1,761 |  22,045 |   5,555 |
|    nsubj   |  7,774 |  17,444 |   4,012 |
| nsubj:pass |    516 |       0 |       0 |
|   nummod   |    489 |   3,295 |     154 |
|     obj    |  5,801 |  23,605 |   9,823 |
|     obl    |  2,784 |  11,577 |   3,357 |
|    punct   | 10,494 |  39,016 |  13,073 |
|    root    |  6,332 |  27,363 |   5,036 |
|  vocative  |      0 |      15 |       0 |
|    xcomp   |      1 |   4,278 |   4,803 |
|    Total   | 80,392 | 350,090 | 132,041 |
