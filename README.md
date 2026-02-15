# Orientation Normalization of Multi-Stain Skin Tissue Cross-Sections
This repository contains all code to support the paper:  

***"Orientation Normalization of Multi-Stain Skin Tissue Cross-Sections"***  

Accepted at MIDL 2026.

[[`OpenReview`](https://openreview.net/forum?id=SUgnMdiJ2q)]


<div align="center">
  <img width="100%" alt="Method" src=".github\examples.gif">
</div>

## Contents
The repository contains two folders:
- `dataset_curation` contains all python files that were used for annotation and preprocessing of the dataset.
- `models` contains all python files that were used for training and evaluation of the different rotation angle prediction approaches.
  - Parameters for the rotation angle prediction models trained as part of this project are available from the corresponding [HuggingFace repository](https://huggingface.co/RTLucassen/orientation_normalization).
