# МОДЕЛИРОВАНИЕ СЕМАНТИЧЕСКОЙ ЦЕНТРАЛЬНОСТИ ЛЕКСЕМ КАК ИНСТРУМЕНТА ИССЛЕДОВАНИЯ ОРГАНИЗАЦИИ МЕНТАЛЬНОГО ЛЕКСИКОНА

*(Modeling Semantic Centrality of Lexemes as a Tool for Investigating the Organization of the Mental Lexicon)*

This repository contains the datasets and supplementary materials accompanying the conference paper.

## Repository contents

### Datasets

- **russian_600_lexemes.csv** – Dataset of 600 Russian lexemes representing frequent concepts from various semantic domains.
- **central_peripheral_lexemes_ipm.csv** – Frequency (IPM) values for the ten most central and ten most peripheral lexemes according to the Russian National Corpus.

## Methodology

Semantic centrality was calculated using pre-trained fastText embeddings. Cosine similarity was computed between all pairs of lexemes, and the semantic centrality of each lexeme was defined as the average cosine similarity between the target lexeme and all other lexemes in the analyzed dataset.
