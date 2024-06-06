# MedSIM-with-MedSAM
## Overview
MedSIM: Deformable Medical Image Registration Framework

MedSIM is an advanced framework designed for deformable medical image registration. It integrates state-of-the-art techniques like TransMorph and SAM-Med3D to ensure high accuracy and reliability in aligning medical images. MedSIM operates by aligning unaligned images to their correct anatomical positions through sophisticated encoding and transformation processes.

## Features
Image Registration: Aligns unaligned medical images to their anatomical accuracy using deep learning models.
Advanced Encoders: Incorporates the SAM-Med3D encoder which utilizes spatial attention mechanisms for improved feature extraction.
Evaluation Metrics: Utilizes the NCC and R metrics, including the Dice Score and Continuity, to evaluate the performance of the image registration.

## Results
MedSIM has been tested against several benchmarks, showing superior performance, particularly in metrics like the Dice score and SAM score. For detailed results, see our results section.

<div align="center">
    <img src="https://github.com/MedSIM-with-MedSAM/MedSIM-with-MedSAM/assets/143985307/bfc35866-feee-4a0e-a514-89a2f5f31ea2" width="50%" height="auto">
</div>

## Contributions
MedSIM introduces the novel SAM score loss which leverages semantic information without the need for segmentation maps. This enhances both the performance plausibility and the dice score metrics significantly.

## Limitations & Future Work
While MedSIM provides a robust platform for medical image registration, it currently requires further testing on multi-modal data and could benefit from multi-level analysis in the MedSAM encoder. Continued training over longer epochs is suggested to further enhance performance.

## Discussion
MedSIM addresses significant challenges in the field and proposes a robust solution that improves both accuracy and efficiency.
