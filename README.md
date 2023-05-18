<div align="center">
# Super-Resolution of BVOC Emission Maps Via Domain Adaptation

<img src=./system.pdf  width="60%", align="center">
<div align="left">

Official Repository of
 **Super-Resolution of BVOC Emission Maps Via Domain Adaptation** paper, accepted at IGARSS 2023 and available at IEEExplore.
 
## Abstract

For more details, please see: "[Super-Resolution of BVOC Emission Maps Via Domain Adaptation](IEEE Link)"

## Supplementary materials
### Dataset Comparison
###### Aggregation Differences
<div align="center">
<img src=./experiments/dataset_difference.pdf  width="60%", align="center">
<div align="left">
###### Spectral Differences

### Preliminary Results
###### Resolution Effect
<div align="center">
<img src=./experiments/resolution_comparison_1.pdf  width="60%", align="center">

<img src=./experiments/resolution_comparison_2.pdf  width="60%", align="center">
<div align="left">

### Data Tranformation Adaptation

### Network Operator Adaptation
###### Injection
Normal
<img src=./experiments/injection_comparison_good.pdf  width="100%", align="center">

Outlier
<img src=./experiments/injection_comparison_bad.pdf  width="100%", align="center">
###### Performance Comparison
<div align="center">
<img src=./experiments/exp_2_val_mix.pdf  width="70%", align="center">
<div align="left">

###### Generalization on Simulated Data
###### GOME-2 vs OMI network cross test
Using Net and Trans of one dataset to infer the other.

OMI data with GOME-2 Net: 
SSIM / NMSE 0.981 / -18.65

GOME-2 data with OMI Net: 
SSIM / NMSE 0.969 / -15.24

## Citation
```BibTex
@article{giganti2023bvoc-da,
      title={Super-Resolution of BVOC Emission Maps Via Domain Adaptation}, 
      author={Antonio Giganti, Sara Mandelli, Paolo Bestagini, Marco Marcon, Stefano Tubaro},
      year={2023},
      DA COMPLETARE
}
```

## Related Works on BVOC
A. Giganti, S. Mandelli, P. Bestagini, et al., “Super-resolution of
bvoc maps by adapting deep learning methods,” arXiv preprint, 2023

[![arXiv](https://img.shields.io/badge/arXiv-2302.07570v2-b31b1b.svg)](https://arxiv.org/abs/2302.07570v2)

A. Giganti, S. Mandelli, P. Bestagini, et al., “Multi-BVOC Super-Resolution Exploiting Compounds Inter-Connection,” 2023

[![Submitted](https://img.shields.io/badge/WIP-Submitted-yellow)]()

### Acknowledgement
This work was supported by the Italian Ministry of University and
Research (MUR) and the European Union (EU) under the PON/REACT project.

<img src="./logos/ispl_logo.pdf" width="100px" alt="logo"></img>
<img src="./logos/polimi_logo.pdf" width="200px" alt="logo"></img>
<img src="./logos/pon_logo.pdf" width="150px" alt="logo"></img>
<img src="./logos/mur_logo.pdf" width="70px" alt="logo"></img>
<img src="./logos/ue_logo.pdf" width="100px" alt="logo"></img>




