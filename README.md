# Istanbul Building Dataset V2: A Morphologically Diverse VHR Benchmark for Urban Building Segmentation
## Overview
Istanbul Building Dataset V2 is a very-high-resolution satellite image dataset for building segmentation in Istanbul, Türkiye. It includes challenging urban settings such as dense historical areas, connected building blocks, irregular roof geometries, and high-rise buildings.
The dataset extends the original Istanbul Building Dataset (V1) by incorporating additional urban morphologies.

<img width="1130" height="673" alt="image" src="https://github.com/user-attachments/assets/59e05ae8-d9a1-48b2-8e0e-911a68491cce" />

Fig. 1. Spatial distribution of the V1 and V2 datasets in Istanbul and representative building annotations from V2, including the Historic Peninsula, the Grand
Bazaar, ITU Tas¸kıs¸la, the S¨uleymaniye Mosque, and tall buildings.

## Dataset
- **Study area:** Istanbul, Türkiye
- **Spatial resolution:** 0.5 m
- **Patch size:** 512 × 512 pixels
- **Annotations:** Manually delineated, image-aligned building roof boundaries and corresponding binary masks

The dataset contains 1,381 patches: 967 for training, 276 for validation, and 138 for testing.
## Benchmark Experiments
The study evaluates CNN-based segmentation architectures (U-Net, UNet++, DeepLabV3+, FPN, and PSPNet) and SegFormer with an MiT-B2 encoder. Experiments include in-domain evaluation, cross-dataset testing, and boundary-focused assessment.
Segmentation performance is assessed using pixel-level IoU, F1-score, and Boundary IoU.

## Availability
## Citation
