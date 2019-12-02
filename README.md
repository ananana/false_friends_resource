# false_friends_resource
Automatically built lexicon of false friends in 6 languages: Romanian, French, Italian, Spanish, Portuguese, English.

The resource contains one file for each pair of languages among the languages considered. Files are formatted as csvs; for a pair of languages `lang1-lang2`, the corresponding file is `<lang1>_<lang2>.csv`, and the columns correspond to:

- word in `lang1`
- corresponding false friend in `lang2`
- a "falseness" score which ranges from  0 to 1 and is lower for false friends that are closer in meaning and higher for more distant false friends.
