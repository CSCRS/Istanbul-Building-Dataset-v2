# Istanbul Building Dataset V2: A Morphologically Diverse VHR Benchmark for Urban Building Segmentation
## Overview
Istanbul Building Dataset V2 is a very-high-resolution satellite image dataset for building segmentation in Istanbul, Türkiye. It includes challenging urban settings such as dense historical areas, connected building blocks, irregular roof geometries, and high-rise buildings.
The dataset extends the original Istanbul Building Dataset (V1) by incorporating additional urban morphologies.

<img width="1130" height="673" alt="image" src="https://github.com/user-attachments/assets/59e05ae8-d9a1-48b2-8e0e-911a68491cce" />

Fig. 1. Spatial distribution of the V1 and V2 datasets in Istanbul and representative building annotations from V2, including the Historic Peninsula, the Grand
Bazaar, ITU Taşkışla, the Süleymaniye Mosque, and tall buildings.

## Dataset
- **Study area:** Istanbul, Türkiye
- **Spatial resolution:** 0.5 m
- **Patch size:** 512 × 512 pixels
- **Annotations:** Manually delineated, image-aligned building roof boundaries and corresponding binary masks

The dataset contains 1,381 patches: 967 for training, 276 for validation, and 138 for testing.
## Benchmark Experiments
Seven segmentation architectures are compared in-domain: U-Net, UNet++, DeepLabV3+, FPN, PSPNet, SegFormer (MiT-B2), and a hybrid U-Net with a MiT-B2 encoder. Additional cross-dataset and boundary-focused evaluations are conducted using U-Net. 
Performance is assessed using pixel-level IoU, F1-score, and Boundary IoU, as appropriate for each experiment.

## Model Weights
Trained model weights are available for U-Net, UNet++, DeepLabV3+, FPN, PSPNet, SegFormer, and U-Net (MiT-B2).
All checkpoints correspond to epoch 50 and were used to obtain the V2 test results reported in the paper.
**[Download Model Weights](https://github.com/CSCRS/Istanbul-Building-Dataset-v2/releases/tag/v2.0.0)**

## Availability
The dataset access link will be provided here once confirmed.

## Acknowledgments
This work was supported by the GRSS Quality Remote Sensing Data Creation initiative.

## Citation
The associated manuscript is currently under review. Full citation details will be added upon publication.
