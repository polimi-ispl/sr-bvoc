<h1 style="text-align: center;">
Super-Resolution of BVOC Emission Maps Via Domain Adaptation
</h1>

<p align="center" width="100%"><img width="50%" src="./system.png"></p>

Official Repository of
 **Super-Resolution of BVOC Emission Maps Via Domain Adaptation** paper, accepted at IGARSS 2023 and available at IEEExplore.
 
## Abstract

For more details, please see: "[Super-Resolution of BVOC Emission Maps Via Domain Adaptation](IEEE Link)"

## Supplementary materials
### Dataset Comparison
###### Aggregation Differences
<p align="center" width="100%"><img width="50%" src="./experiments/dataset_difference.png"></p>

###### Spectral Differences

### Preliminary Results
###### Resolution Effect
<p align="center" width="100%"><img width="50%" src="./experiments/resolution_comparison_1.png"></p>
<p align="center" width="100%"><img width="50%" src="./experiments/resolution_comparison_2.png"></p>

### Data Tranformation Adaptation

### Network Operator Adaptation
###### Injection
Normal
<p align="center" width="100%"><img width="80%" src="./experiments/injection_comparison_good.png"></p>

Outlier
<p align="center" width="100%"><img width="80%" src="./experiments/injection_comparison_bad.png"></p>

###### Performance Comparison
<p align="center" width="100%"><img width="50%" src="./experiments/exp_2_val_mix.png"></p>


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

<img src="./logos/ispl_logo.png" width="100px" alt="logo"></img>
<img src="./logos/polimi_logo.png" width="200px" alt="logo"></img>
<img src="./logos/pon_logo.png" width="150px" alt="logo"></img>
<img src="./logos/mur_logo.png" width="70px" alt="logo"></img>
<img src="./logos/ue_logo.png" width="100px" alt="logo"></img>




