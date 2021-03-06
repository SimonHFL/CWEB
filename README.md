# CWEB (Corrected Websites) corpus

CWEB is an evaluation dataset for grammatical error correction (GEC) consisting of website text generated by English speakers of varying levels of proficiency.
In contains 13,574 sentences from 1,078 websites which have been annotated for grammatical errors.

Description of this corpus can be found in the paper:

[Grammatical Error Correction in Low Error Density Domains: A New Benchmark and Analyses](https://www.aclweb.org/anthology/2020.emnlp-main.680.pdf)  
Simon Flachs, Ophélie Lacroix, Helen Yannakoudakis, Marek Rei and Anders Søgaard
In Proceedings of the 2020 Conference on Empirical Methods in Natural Language Processing (EMNLP 2020)

Please cite this paper when using the dataset.

# Data
* `data/raw` contains the untokenized parallel data
* `data/tokenized` contains the tokenized parallel data (tokenized with Spacy 1.9)
* `data/m2` contains M2 files created with [ERRANT](https://github.com/chrisjbryant/errant) against annotators combined and individually.

# Questions
Please e-mail Simon Flachs (flachs[at]di.ku.dk).

# License
This work is licensed under a 
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License.](https://creativecommons.org/licenses/by-nc-sa/4.0/)
