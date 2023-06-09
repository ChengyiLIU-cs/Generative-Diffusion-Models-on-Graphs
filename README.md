# Generative Diffusion Models on Graphs: Methods and Applications
> 
> Welcome to the [**Generative Diffusion Models on Graphs: Methods and Applications**](https://arxiv.org/abs/2302.02591) repository! 
> This repository serves as a comprehensive collection of resources related to diffusion models applied to graphs. 
>

## Table of Contents
- [Generative Diffusion Models on Graph](#Generative-Diffusion-Models-on-Graph)
  - [SMLD on Graphs](#SMLD-on-Graphs)
  - [DDPM on Graphs](#DDPM-on-Graphs)
  - [SGM on Graphs](#SGM-on-Graphs)
- [Diffusion Models on Graphs: Applications](#Diffusion-Models-on-Graphs:-Applications)
  - [Molecule Modeling](#Molecule-Modeling)
    - [Molecule Conformation Generation](#Molecule-Conformation-Generation)
      - [SMLD](#smld1) 
      - [DDPM](#ddpm1)
      - [SGM](#sgm1)
    - [Molecular Docking](#Molecule-Docking)
      - [DDPM](#ddpm2)
      - [SGM](#sgm2)
  - [Protein Modeling](#Protein-Modeling)
    - [Protein Generation](#Protein-Generation)
      - [DDPM](#ddpm3)
      - [SGM](#sgm3)
    - [Protein-ligand Complex Structure Predictiong](#Protein-ligand-Complex-Structure-Predictiong)

## Diffusion models on molecular and protein generations

![Diffusion_models_on_molecular_and_protein_generations](Figure/Graph-Diffusion.png)

## Generative Diffusion Models on Graph

### SMLD on Graphs

**Permutation Invariant Graph Generation via Score-Based Generative Modeling** \
*Chenhao Niu, Yang Song, Jiaming Song, Shengjia Zhao, Aditya Grover, Stefano Ermon* \
AISTATS 2021. [[Paper](https://arxiv.org/abs/2003.00638)] [[Github](https://github.com/ermongroup/GraphScoreMatching)] \
2 Mar 2020

**Learning gradient fields for molecular conformation generation** \
*Chence Shi, Shitong Luo, Minkai Xu, Jian Tang* \
ICML 2021. [[Paper](https://arxiv.org/abs/2105.03902)] [[Github](https://github.com/DeepGraphLearning/ConfGF)] \
9 May 2021

### DDPM on Graphs

**Diffusion Models for Graphs Benefit From Discrete State Spaces** \
*Kilian Konstantin Haefeli, Karolis Martinkus, Nathanaël Perraudin, Roger Wattenhofer* \
LoG 2022 and NeurIPS GLFrontiers 2022. [[Paper](https://arxiv.org/abs/2210.01549)] [[Github](https://github.com/kilian888/discrete_dppm_graphs)] \
4 Oct 2022

**DiGress: Discrete Denoising diffusion for graph generation** \
*Clement Vignac<sup>1</sup>, Igor Krawczuk<sup>1</sup>, Antoine Siraudin, Bohan Wang, Volkan Cevher, Pascal Frossard* \
ICLR 2023. [[Paper](https://arxiv.org/abs/2209.14734)] [[Github](https://github.com/cvignac/digress)] \
29 Sep 2022

### SGM on Graphs

**GraphGDP: Generative Diffusion Processes for Permutation Invariant Graph Generation** \
*Han Huang, Leilei Sun, Bowen Du, Yanjie Fu, Weifeng Lv* \
IEEE ICDM 2022. [[Paper](https://arxiv.org/abs/2212.01842)] [[Github](https://github.com/graph-0/graphgdp)] \
4 Dec 2022

**Score-based Generative Modeling of Graphs via the System of Stochastic Differential Equations** \
*Jaehyeong Jo, Seul Lee, Sung Ju Hwang* \
ICML, 2022.  [[Paper](https://arxiv.org/abs/2202.02514)] [[Github](https://github.com/harryjo97/gdss)] \
5 Feb 2022

**Fast Graph Generative Model via Spectral Diffusion** \
*Tianze Luo, Zhanfeng Mo, Sinno Jialin Pan* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.08892)] \
16 Nov 2022

**Score-based graph generative modeling with self-guided latent diffusion** \
*Ling Yang, Zhilong Zhang, Wentao Zhang, and Shenda Hong* \
OpenReview. [[Paper](https://openreview.net/forum?id=AykEgQNPJEK)] \
02 Feb 2023

## Diffusion Models on Graphs: Applications

### Molecule Modeling

#### Molecule Conformation Generation

#### <a id="smld1"> SMLD </a>

**MDM: Molecular Diffusion Model for 3D Molecule Generation** \
*Lei Huang, Hengtong Zhang, Tingyang Xu, Ka-Chun Wong* \
Submitted to AAAI'23. [[Paper](https://arxiv.org/abs/2209.05710)] \
13 Sep 2022

#### <a id="ddpm1"> DDPM </a>

**GeoDiff: a Geometric Diffusion Model for Molecular Conformation Generation** \
*Minkai Xu, Lantao Yu, Yang Song, Chence Shi, Stefano Ermon, Jian Tang* \
ICLR 2022. [[Paper](https://arxiv.org/abs/2203.02923)] [[Github](https://github.com/MinkaiXu/GeoDiff)] \
6 Mar 2022

**Equivariant Diffusion for Molecule Generation in 3D** \
*Emiel Hoogeboom, Vıctor Garcia Satorras, Clement Vignac, and Max Welling* \
ICML 2022. [[Paper](https://arxiv.org/abs/2203.17003)] [[Github](https://github.com/ehoogeboom/e3_diffusion_for_molecules)] \
31 Mar 2022

**Equivariant Energy-Guided SDE for Inverse Molecular Design** \
*Fan Bao, Min Zhao, Zhongkai Hao, Peiyao Li, Chongxuan Li, Jun Zhu* \
ICLR 2023. [[Paper](https://arxiv.org/abs/2209.15408)] [[Github](https://github.com/gracezhao1997/EEGSDE)] \
30 Sep 2022

#### <a id="sgm1"> SGM </a>

**Predicting Molecular Conformation via Dynamic Graph Score Matching** \
*Shitong Luo, Chence Shi, Minkai Xu, Jian Tang* \
NeurIPS 2021. [[Paper](https://proceedings.neurips.cc/paper/2021/hash/a45a1d12ee0fb7f1f872ab91da18f899-Abstract.html)] \
22 May 2021

**Torsional Diffusion for Molecular Conformer Generation** \
*Bowen Jing, Gabriele Corso, Regina Barzilay, Tommi S. Jaakkola* \
NeurIPS 2022. [[Paper](https://arxiv.org/abs/2206.01729)] [[Github](https://github.com/gcorso/torsional-diffusion)] \
1 Jun 2022

**Exploring Chemical Space with Score-based Out-of-distribution Generation** \
*Seul Lee, Jaehyeong Jo, Sung Ju Hwang* \
ICML 2023. [[Paper](https://arxiv.org/abs/2206.07632)] [[Github](https://github.com/seullee05/mood)] \
6 Jun 2022

**Diffusion-based Molecule Generation with Informative Prior Bridges** \
*Lemeng Wu<sup>1</sup>, Chengyue Gong<sup>1</sup>, Xingchao Liu, Mao Ye, Qiang Liu* \
NeurIPS 2022. [[Paper](https://arxiv.org/abs/2209.00865)] \
2 Sep 2022

#### Molecule Docking

#### <a id="ddpm2"> DDPM </a>

**Equivariant 3D-Conditional Diffusion Models for Molecular Linker Design** \
*Ilia Igashov, Hannes Stärk, Clément Vignac, Victor Garcia Satorras, Pascal Frossard, Max Welling, Michael Bronstein, Bruno Correia* \
NeurIPS 2022. [[Paper](https://arxiv.org/abs/2210.05274)] [[Github](https://github.com/gcorso/torsional-diffusion)] \
11 Oct 2022

**DiffBP: Generative Diffusion of 3D Molecules for Target Protein Binding** \
*Haitao Lin<sup>1</sup>, Yufei Huang<sup>1</sup>, Meng Liu, Xuanjing Li, Shuiwang Ji, Stan Z. Li* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.11214)] \
21 Nov 2022

**Pocket-specific 3D Molecule Generation by Fragment-based Autoregressive Diffusion Models** \
*Xingang Peng, Jiaqi Guan, Jian Peng, Jianzhu Ma* \
OpenReview 2022. [[Paper](https://openreview.net/forum?id=HGsoe1wmRW5)] \
02 Feb 2023

**3D Equivariant Diffusion for Target-Aware Molecule Generation and Affinity Prediction** \
*Jiaqi Guan, Wesley Wei Qian, Xingang Peng, Yufeng Su, Jian Peng, Jianzhu Ma* \
ICLR 2023. [[Paper](https://arxiv.org/abs/2303.03543)] [[Github](https://github.com/guanjq/targetdiff)] \
6 Mar 2023

#### <a id="sgm2"> SGM </a>

**DiffDock: Diffusion Steps, Twists, and Turns for Molecular Docking** \
*Gabriele Corso, Hannes Stärk, Bowen Jing, Regina Barzilay, Tommi Jaakkola* \
ICLR 2023. [[Paper](https://arxiv.org/abs/2210.01776)] [[Github](https://github.com/gcorso/diffdock)] \
4 Oct 2022

###  Molecule Modeling

#### Protein Generation

#### <a id="ddpm3"> DDPM </a>

**Protein Representation Learning by Geometric Structure Pretraining** \
*Zuobai Zhang, Minghao Xu, Arian Jamasb, Vijil Chenthamarakshan, Aurelie Lozano, Payel Das, Jian Tang* \
arXiv 2022.. [[Paper](https://arxiv.org/abs/2203.06125)] [[Github](https://github.com/deepgraphlearning/gearnet)]\
11 Mar 2022

**Protein Structure and Sequence Generation with Equivariant Denoising Diffusion Probabilistic Models** \
*Namrata Anand, Tudor Achim* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2205.15019)] [[Project](https://nanand2.github.io/proteins/)] [[Github](https://github.com/lucidrains/ddpm-ipa-protein-generation)] \
26 May 2022

**Diffusion probabilistic modeling of protein backbones in 3D for the motif-scaffolding problem** \
*Brian L. Trippe<sup>1</sup>, Jason Yim<sup>1</sup>, Doug Tischer, Tamara Broderick, David Baker, Regina Barzilay, Tommi Jaakkola* \
ICLR 2023. [[Paper](https://arxiv.org/abs/2206.04119)] [[Github](https://github.com/luost26/diffab)]\
8 Jun 2022

**Antigen-Specific Antibody Design and Optimization with Diffusion-Based Generative Models** \
*Shitong Luo<sup>1</sup>, Yufeng Su<sup>1</sup>, Xingang Peng, Sheng Wang, Jian Peng, Jianzhu Ma* \
NeurIPS 2022. [[Paper](https://www.biorxiv.org/content/10.1101/2022.07.10.499510v1)] \
11 Jul 2022

**Protein structure generation via folding diffusion** \
*Kevin E. Wu, Kevin K. Yang, Rianne van den Berg, James Y. Zou, Alex X. Lu, Ava P. Amini* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2209.15611)] [[Github](https://arxiv.org/abs/2209.15611)]\
30 Sep 2022

#### <a id="sgm3"> SGM </a>



#### Protein-ligand Complex Structure Predictiong

> If you find our survey useful for your research, please cite the following paper:
```
@article{fan2023generative,
  title={Generative diffusion models on graphs: Methods and applications},
  author={Fan, Wenqi and Liu, Chengyi and Liu, Yunqing and Li, Jiatong and Li, Hang and Liu, Hui and Tang, Jiliang and Li, Qing},
  journal={arXiv preprint arXiv:2302.02591},
  year={2023}
}
```
