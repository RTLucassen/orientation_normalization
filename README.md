# Orientation Normalization of Multi-Stain Skin Tissue Cross-Sections
This repository contains all code to support the paper:  

***"Orientation Normalization of Multi-Stain Skin Tissue Cross-Sections"***  

Accepted at MIDL 2026.

[[`OpenReview`](https://openreview.net/forum?id=SUgnMdiJ2q)] [[`PLMR`](https://proceedings.mlr.press/v315/topolnjak26a.html)]


<div align="center">
  <img width="100%" alt="Method" src=".github\examples.gif">
</div>

## Contents
The repository contains two folders:
- `dataset_curation` contains all python files that were used for annotation and preprocessing of the dataset.
- `models` contains all python files that were used for training and evaluation of the different rotation angle prediction approaches.
  - Parameters for the rotation angle prediction models trained as part of this project are available from the corresponding [HuggingFace repository](https://huggingface.co/RTLucassen/orientation_normalization).

## Citing
If you found our work useful in your research, please consider citing our paper:
```
@InProceedings{topolnjak2026orientation,
  title={Orientation Normalization of Multi-Stain Skin Tissue Cross-Sections},
  author={Topolnjak, Ema and Paulides, Evi and Blokx, Willeke A. M. and Veta, Mitko and Lucassen, Ruben T.},
  booktitle={Proceedings of The 9th International Conference on Medical Imaging with Deep Learning},
  pages={322--341},
  year={2026},
  volume={315},
  publisher={PMLR},
}
```
