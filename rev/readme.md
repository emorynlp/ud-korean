# Penn Korean Universal Dependency Treebank (PKT-UD) Manual Revision
##### IWPT2020@ACL'20

This repo contains manual revision of Penn Korean Universal Treebank (PKT-UD), with `#TOKEN#`, `#LEMMA#`, `#MORPHEMES#` columns masked.

Please see details [here](https://aclanthology.org/2020.iwpt-1.13/).

```
@inproceedings{oh-etal-2020-analysis,
    title = "Analysis of the {P}enn {K}orean {U}niversal {D}ependency Treebank ({PKT}-{UD}): Manual Revision to Build Robust Parsing Model in {K}orean",
    author = "Oh, Tae Hwan  and
      Han, Ji Yoon  and
      Choe, Hyonsu  and
      Park, Seokwon  and
      He, Han  and
      Choi, Jinho D.  and
      Han, Na-Rae  and
      Hwang, Jena D.  and
      Kim, Hansaem",
    booktitle = "Proceedings of the 16th International Conference on Parsing Technologies and the IWPT 2020 Shared Task on Parsing into Enhanced Universal Dependencies",
    month = jul,
    year = "2020",
    address = "Online",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2020.iwpt-1.13",
    doi = "10.18653/v1/2020.iwpt-1.13",
    pages = "122--131",
    abstract = "In this paper, we first open on important issues regarding the Penn Korean Universal Treebank (PKT-UD) and address these issues by revising the entire corpus manually with the aim of producing cleaner UD annotations that are more faithful to Korean grammar. For compatibility to the rest of UD corpora, we follow the UDv2 guidelines, and extensively revise the part-of-speech tags and the dependency relations to reflect morphological features and flexible word- order aspects in Korean. The original and the revised versions of PKT-UD are experimented with transformer-based parsing models using biaffine attention. The parsing model trained on the revised corpus shows a significant improvement of 3.0{\%} in labeled attachment score over the model trained on the previous corpus. Our error analysis demonstrates that this revision allows the parsing model to learn relations more robustly, reducing several critical errors that used to be made by the previous model.",
}
```
