# FakeOnlineTCC-Corpus

This repository contains 2 folders, each with two versions of the same corpus:
- 'FullTexts' folder, which contains the full texts originally collected from their websites. Inside the folder there are 2 mode folders:
  - 'Original' folder, which contains the original files as collected.
  - 'Preprocessed' folder, which contains the pre-processed texts, such as removed portuguese stopwords or accent.

- 'SizeNormalizedTexts' folder, which contains the truncated texts, where each fake-true pair had the longer text truncated to match the size of the smaller texts. Which was done to avoid bias in machine learning experiments. Inside there are the same 2 folders as 'FullTexts': 'Original' and 'Preprocessed'
