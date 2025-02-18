# GMFCS_STGCN

This repository contains the code implementation for the research paper titled *Motor Function Assessment of Children with
Cerebral Palsy using Monocular Video*. This paper was presented at IEEE-EMBS International Conference on Body Sensor Networks (IEEE BSN 2023).

Also, it contains the additional parts in TSNRE folder, for an extended journal paper under review. 


## Authors
Peijun Zhao, Department of Mechanical Engineering, Massachusetts Institute of Technology

Moises Alencastre-Miranda, Department of Mechanical Engineering, Massachusetts Institute of Technology

Zhan Shen, Robotics Institute, University of Michigan

Ciaran O'Neill, Department of Mechanical Engineering, Massachusetts Institute of Technology

David Whiteman, Takeda

Javier Gervas-Arruga, Takeda

Hermano Igo Krebs, Department of Mechanical Engineering, Massachusetts Institute of Technology



## Abstract

The assessment of movement abilities in individuals with neurological disorders is a critical task in clinical practice. Currently, clinical assessments are time-consuming and rely on qualitative scales typically conducted by trained clinicians. Moreover, these assessments offer only coarse snapshots of a person’s abilities, failing to track the minutiae of recovery over time. To overcome these limitations, we propose a machine learning approach based on spatial-temporal graph convolutional network (STGCN) to extract movement features from pose data obtained from monocular videos collected with mobile devices (e.g., smartphones, tablets). Our proposed method achieves an accuracy of 76.6% in evaluating children with Cerebral Palsy (CP) using the Gross Motor Function Classification System (GMFCS), a 5% improvement in accuracy compared to current state-of-the-art methods, and shows substantial agreement
with professional assessments based on the weighted Cohen’s Kappa (κlw = 0.733). Furthermore, the proposed method can be efficiently implemented on a wide range of mobile devices in real-time or near real-time.

## Paper Link
https://dspace.mit.edu/bitstream/handle/1721.1/152149/_BSN__Monocular_based_Gross_Motor_Function_Assessment%20%281%29%5B58%5D.pdf

## Code Overview

The code in this repository corresponds to the experiments conducted in the paper. It is organized into the following directories:

- **`machine_learning/`**: Neural network definitions and training code. 
- **`preprocessing/`**: Preprocessing Scripts.
- **`.devcontainer/`**: A Docker container setup for Visual Studio Code users. See the details [here](.devcontainer/README.md).

## Ackowledgement
This research was supported by Takeda Development Center Americas, INC. (successor in interest to Millennium Pharmaceuticals, INC.) \- MIT Grant \#6947514.


## Citation

If you find this code useful in your research, please consider citing the paper.
```
@inproceedings{zhao2023motor,
  title={Motor Function Assessment of Children with Cerebral Palsy using Monocular Video},
  author={Zhao, Peijun and Alencastre-Miranda, Moises and Shen, Zhan and O’Neill, Ciaran and Whiteman, David and Gervas-Arruga, Javier and Krebs, Hermano Igo},
  booktitle={Proceedings of the IEEE-EMBS International Conference on Body Sensor Networks},
  year={2023}
}
```
