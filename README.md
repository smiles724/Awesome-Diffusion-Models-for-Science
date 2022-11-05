# Awesome Diffusion Models for Science
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)]([https://github.com/hee9joon/Awesome-Diffusion-Models](https://github.com/smiles724/Awesome-Diffusion-Models-in-Molecules)) 
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Made With Love](https://img.shields.io/badge/Made%20With-Love-red.svg)](https://github.com/chetanraj/awesome-github-badges)

This repository contains a collection of resources and papers on ***Diffusion Models for Science***. For a more comprehensive overview of diffusion-baed models, please refer to [Awesome-Diffusion-Models](https://github.com/heejkoo/Awesome-Diffusion-Models).

# Contents
- [Small Molecules](#small-molecules)
  - [Drug Design](#drug-design)
  - [Molecule Conformation Prediction](#molecule-conformation-prediction)
  - [Molecular Dynamics Simulations](#molecular-dynamics-simulations)
- [Proteins](#proteins)
  - [Protein Structure Prediction](#protein-structure-prediction)
  - [Protein Design](#protein-design)
  - [Antibody Design](#antibody-design)
- [Complex](#complex)
  - [Complex Structure Prediction](#complex-structure-prediction)
- [Materials](#materials)
  - [Materials Design](#materials-design)
- [Physics](#physics)


# Papers
## Small Molecules 
### Drug Design

> **Structure-based Drug Design with Equivariant Diffusion Models** \
> *Arne Schneuing<sup>1</sup>, Yuanqi Du<sup>1</sup>, Charles Harris, Arian Jamasb, Ilia Igashov, Weitao Du, Tom Blundell, Pietro Lió, Carla Gomes, Max Welling, Michael > Bronstein, Bruno Correia* \
> arXiv 2022. [[Paper](https://arxiv.org/abs/2210.13695)] [[Github](https://github.com/arneschneuing/DiffSBDD)]\
> 24 Oct 2022

**Equivariant 3D-Conditional Diffusion Models for Molecular Linker Design** \
*Ilia Igashov, Hannes Stärk, Clément Vignac, Victor Garcia Satorras, Pascal Frossard, Max Welling, Michael Bronstein, Bruno Correia* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.05274)] \
11 Oct 2022

**Equivariant Energy-Guided SDE for Inverse Molecular Design** \
*Fan Bao<sup>1</sup>, Min Zhao<sup>1</sup>, Zhongkai Hao, Peiyao Li, Chongxuan Li, Jun Zhu* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2209.15408)] \
30 Sep 2022

**MDM: Molecular Diffusion Model for 3D Molecule Generation** \
*Lei Huang, Hengtong Zhang, Tingyang Xu, Ka-Chun Wong* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2209.05710)] \
13 Sep 2022

**Diffusion-based Molecule Generation with Informative Prior Bridges** \
*Lemeng Wu<sup>1</sup>, Chengyue Gong<sup>1</sup>, Xingchao Liu, Mao Ye, Qiang Liu* \
NeurIPS 2022. [[Paper](https://arxiv.org/abs/2209.00865)] \
2 Sep 2022

**Equivariant Diffusion for Molecule Generation in 3D** \
*Emiel Hoogeboom<sup>1</sup>, Victor Garcia Satorras<sup>1</sup>, Clément Vignac, Max Welling* \
ICML 2022. [[Paper](https://arxiv.org/abs/2203.17003)] [[Github](https://github.com/ehoogeboom/e3_diffusion_for_molecules)] \
31 Mar 2022


### Molecule Conformation Prediction

**Torsional Diffusion for Molecular Conformer Generation** \
*Bowen Jing, Gabriele Corso, Regina Barzilay, Tommi S. Jaakkola* \
ICLR Workshop 2022. [[Paper](https://arxiv.org/abs/2206.01729)] [[Github](https://github.com/gcorso/torsional-diffusion)] \
1 Jun 2022

**Predicting Molecular Conformation via Dynamic Graph Score Matching** \
*Shitong Luo, Chence Shi, Minkai Xu, Jian Tang* \
NeurIPS 2021. [[Paper](https://proceedings.neurips.cc/paper/2021/hash/a45a1d12ee0fb7f1f872ab91da18f899-Abstract.html)] \
22 May 2021

**GeoDiff: a Geometric Diffusion Model for Molecular Conformation Generation** \
*Minkai Xu, Lantao Yu, Yang Song, Chence Shi, Stefano Ermon, Jian Tang* \
ICLR 2022 oral. [[Paper](https://arxiv.org/abs/2203.02923)] [[Github](https://github.com/MinkaiXu/GeoDiff)] \
6 Mar 2022

### Molecular Dynamics Simulations

**A Score-based Geometric Model for Molecular Dynamics Simulations** \
*Fang Wu<sup>1</sup>, Qiang Zhang<sup>1</sup>, Xurui Jin, Yinghui Jiang, Stan Z. Li* \
CoRR 2022. [[Paper](https://arxiv.org/abs/2204.08672)] \
19 Apr 2022

## Proteins
### Protein Structure Prediction

**Protein structure generation via folding diffusion** \
*Kevin E. Wu, Kevin K. Yang, Rianne van den Berg, James Y. Zou, Alex X. Lu, Ava P. Amini* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2209.15611)] [[Github](https://github.com/microsoft/foldingdiff)] \
30 Sep 2022

### Protein Design

**Protein Sequence and Structure Co-Design with Equivariant Translation** \
*Chence Shi, Chuanrui Wang, Jiarui Lu, Bozitao Zhong, Jian Tang* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.08761)] \
17 Oct 2022

**Diffusion probabilistic modeling of protein backbones in 3D for the motif-scaffolding problem** \
*Brian L. Trippe<sup>1</sup>, Jason Yim<sup>1</sup>, Doug Tischer, Tamara Broderick, David Baker, Regina Barzilay, Tommi Jaakkola* \
CoRR 2022. [[Paper](https://arxiv.org/abs/2206.04119)] \
8 Jun 2022'

**Protein Structure and Sequence Generation with Equivariant Denoising Diffusion Probabilistic Models** \
*Namrata Anand, Tudor Achim* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2205.15019)] [[Project](https://nanand2.github.io/proteins/)] [[Github](https://github.com/lucidrains/ddpm-ipa-protein-generation)] \
26 May 2022

### Antibody Design 

**Antigen-Specific Antibody Design and Optimization with Diffusion-Based Generative Models** \
*Shitong Luo<sup>1</sup>, Yufeng Su<sup>1</sup>, Xingang Peng, Sheng Wang, Jian Peng, Jianzhu Ma* \
NeurIPS 2022. [[Paper](https://www.biorxiv.org/content/10.1101/2022.07.10.499510v1)][[Github](https://github.com/luost26/diffab)] \
11 July 2022

## Complex 
### Complex Structure Prediction

**Dynamic-Backbone Protein-Ligand Structure Prediction with Multiscale Generative Diffusion Models** \
*Zhuoran Qiao, Weili Nie, Arash Vahdat, Thomas F. Miller III, Anima Anandkumar* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2209.15171)] \
30 Sep 2022

## Materials
### Materials Design

**Crystal Diffusion Variational Autoencoder for Periodic Material Generation** \
*Tian Xie<sup>1</sup>, Xiang Fu<sup>1</sup>, Octavian-Eugen Ganea<sup>1</sup>, Regina Barzilay, Tommi Jaakkola*\
NeurIPS 2021. [[Paper](https://arxiv.org/abs/2110.06197)] [[Github](https://github.com/txie-93/cdvae)] \
12 Oct 2021

**Data-driven discovery of novel 2D materials by deep generative models** \
*Peder Lyngby, Kristian Sommer Thygesen* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2206.12159)] \
24 Jun 2022


## Physics 

**Score-based Generative Models for Calorimeter Shower Simulation** \
*Vinicius Mikuni, Benjamin Nachman* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2206.11898)] \
17 Jun 2022




