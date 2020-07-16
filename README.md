# false_friends_resource
Automatically built lexicon of false friends in 6 languages: Romanian, French, Italian, Spanish, Portuguese, English.

The resource contains one file for each pair of languages among the languages considered. Files are formatted as csvs; for a pair of languages `lang1-lang2`, the corresponding file is `<lang1>_<lang2>.csv`, and the columns correspond to:

- word in `lang1`
- corresponding false friend in `lang2`
- a "falseness" score which ranges from  0 to 1 and is lower for false friends that are closer in meaning and higher for more distant false friends.

# Copyright
This dataset is distributed under a Creative Commons license. If using this dataset in your research, please cite the following paper:

Uban, Ana Sabina, and Liviu P. Dinu. ["Automatically Building a Multilingual Lexicon of False Friends With No Supervision."](https://www.aclweb.org/anthology/2020.lrec-1.367.pdf) In Proceedings of The 12th Language Resources and Evaluation Conference, pp. 3001-3007. 2020.

Other relevant work:

Uban, Ana, Alina Maria Ciobanu, and Liviu P. Dinu. ["Studying Laws of Semantic Divergence across Languages using Cognate Sets."](https://www.aclweb.org/anthology/W19-4720.pdf) In Proceedings of the 1st International Workshop on Computational Approaches to Historical Language Change, pp. 161-166. 2019.
