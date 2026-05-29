[![Project Status: Active – The project has reached a stable, usable state and is being actively developed.](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active)  [![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/) [![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)](https://www.python.org/) ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white) [![Ask DeepWiki](https://deepwiki.com/badge.svg)](https://deepwiki.com/tonyjurg/Create_TF-IDF_Text-Fabric_features)

# Create_TF-IDF_Text-Fabric_features

Files used to create a TF-IDF (Term Frequency-Inverse Document Frequency) Text-Fabric featureset for the Nestle 1904 Greek New Testament.

# Features

Feature name | Data type | Available on node | Description | Examples
---|---|---|---|---
[tfidf](https://tonyjurg.github.io/N1904addons/features/tfidf.html)| `str` | `word` | TF–IDF score (× 1,000,000) for this token, calculated using all tokens in the GNT corpus, aggregated per book | `12` `85658`
[tfidfns](https://tonyjurg.github.io/N1904addons/features/tfidfns.html)| `str` | `word` | TF–IDF score (× 1,000,000) for this token, calculated using only non-stopword tokens in the GNT corpus, aggregated per book. | `0` `952564`

## Production notebook

You can view the production notebook on [nbviewer.org](https://nbviewer.org/github/tonyjurg/Create_TF-IDF_Text-Fabric_features/blob/main/create_tfidf_features.ipynb).

Alternative, you can also download it from the [GitHub repository](https://github.com/tonyjurg/Create_TF-IDF_Text-Fabric_features/blob/main/create_tfidf_features.ipynb).

## Usage

These new features are added to the [N1904addons](https://tonyjurg.github.io/N1904addons/features/index.html) dataset.
Information on how to load and use the dataset can be found [here](https://tonyjurg.github.io/N1904addons/loading_the_dataset.html).

## About Text-Fabric

The Text-Fabric framework is designed to facilitate the analysis and manipulation of large-scale textual data, particularly in the context of ancient languages and biblical texts. The engine of Text-Fabric is its powerful Python library, which provides a comprehensive set of tools for processing and querying structured text data efficiently. The software package is accessible at [https://github.com/annotation/text-fabric](https://github.com/annotation/text-fabric).

## License

This notebook is released under the [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://github.com/tonyjurg/Create_TF-IDF_Text-Fabric_features/blob/main/LICENSE.md)

## Citation

If you use this repository in your academic work, please [cite it](CITATION.cff).

