# OpenMAP-T1
![Figure3](https://github.com/OishiLab/OpenMAP-T1/assets/64403395/2ca86ddd-fe18-4ca5-b359-904cba17e44b)

[![](http://img.shields.io/badge/DOI-00.0000/00000-B31B1B.svg)](https://www.biorxiv.org/)
[![](https://img.shields.io/badge/under%20review-ISMRM2024-%2300629B%09)](https://www.ismrm.org/)
[![IEEE Xplore](https://img.shields.io/badge/under%20review-Imaging%20Neuroscience-%2300629B%09)](https://janeway.imaging-neuroscience.org/)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1fmfkxxZjChExnl5cHITYkNYgTu3MZ7Ql#scrollTo=xwZxyL5ewVNF)

**OpenMAP-T1: A Rapid Deep-Learning Approach to Parcellate 280 Anatomical Regions to Cover the Whole Brain**<br>
**Author**: Kei Nishimaki, [Kengo Onda](https://researchmap.jp/kengoonda?lang=en), Kumpei Ikuta, [Yuto Uchida](https://researchmap.jp/uchidayuto), [Susumu Mori](https://www.hopkinsmedicine.org/profiles/details/susumu-mori), [Hitoshi Iyatomi](https://iyatomi-lab.info/english-top), [Kenichi Oishi](https://www.hopkinsmedicine.org/profiles/details/kenichi-oishi)<br>

The Russell H. Morgan Department of Radiology and Radiological Science, The Johns Hopkins University School of Medicine, Baltimore, MD, USA <br>
Department of Applied Informatics, Graduate School of Science and Engineering, Hosei University, Tokyo, Japan <br>
The Richman Family Precision Medicine Center of Excellence in Alzheimer's Disease, Johns Hopkins University School of Medicine, Baltimore, MD, USA<br>

**Abstract**: *This study introduces OpenMAP-T1, a deep learning-based method for rapid and accurate whole brain parcellation in T1-weighted brain MRI, aiming to overcome the limitations of conventional normalization-to-atlas-based approaches and multi-atlas label-fusion (MALF) techniques. Brain image parcellation is a fundamental process in neuroscientific and clinical research, enabling detailed analysis of specific cerebral regions. Normalization-to-atlas-based methods have been employed for this task, but they face limitations due to variations in brain morphology, especially in pathological conditions. The MALF improved the accuracy of the image parcellation and robustness to variations in brain morphology but at the cost of high computational demand that requires lengthy processing time. OpenMAP-T1 integrates several convolutional neural network models across six phases: preprocessing, cropping, skull stripping, parcellation, hemisphere segmentation, and final merging. This process involves standardizing MRI images, isolating the brain tissue, and parcellating it into 280 anatomical structures that cover the whole brain, including detailed gray and white matter structures, while simplifying the parcellation processes and incorporating robust training to handle various scan types and conditions. The OpenMAP-T1 was tested on eight available open resources, including real-world clinical images, demonstrating robustness across different datasets with variations in scanner types, magnetic field strengths, and image processing techniques like defacing. Compared to existing methods, OpenMAP-T1 significantly reduced the processing time per image from several hours to less than 90 seconds without compromising accuracy. It was particularly effective in handling images with intensity inhomogeneity and varying head positions, conditions commonly seen in clinical settings. The adaptability of OpenMAP-T1 to a wide range of MRI datasets and robustness to various scan conditions highlight its potential as a versatile tool in neuroimaging.*

Paper: Not yet<br>
Submitted for publication in the **2024 ISMRM Annual Meeting** and **Imaging Neuroscience**<br>

## Version
| Version | Release Date  | Download                                  |
|---------|---------------|-------------------------------------------|
| 2.0.0   |               |                                           |
| 1.0.0   | December 2023 | https://github.com/OishiLab/OpenMAP-T1-V1 |

## Supplementary information
![supplementary_level](https://github.com/OishiLab/OpenMAP-T1/assets/64403395/0fcb0fb1-af15-4e6e-83b9-d8f64e27307c)
The OpenMAP-T1 parcellate the entire brain into five hierarchical structural levels, with the coarsest level comprising eight structures and the finest level comprising 280 structures. Changing these levels is easy using [ROIEditor](https://www.mristudio.org/installation.html).


## Citation
```
@article{nishimaki2024openmap-t1,
  title={OpenMAP-T1: A Rapid Deep-Learning Approach to Parcellate 280 Anatomical Regions to Cover the Whole Brain},
  author={Kei Nishimaki, Kengo Onda, Kumpei Ikuta, Jill Chotiyanonta, Yuto Uchida, Susumu Mori, Hitoshi Iyatomi, Kenichi Oishi},
  journal={~~~~},
  year={2024},
  publisher={~~~~}
}
```