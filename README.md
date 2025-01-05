# Breast Cancer Classifier 

## Overview

Mammograms are x-rays of the breast that are crucial in the identification process of breast cancer. However, conditions like dense breast tissue and the existence of benign tumors can complicate the detection of cancer. To aid in the diagnosis process, this project is intended to detect breast cancer with a given mammogram.

The zip file contains the Matlab code, the processed dataset images (in a folder named 'imagestouse') as well as an example of a cancerous and noncancerous mammogram (named 'cancerous.png' and 'noncancerous.png' respectively).

## Installation

To properly test the classifer, the program requires MATLAB R2024b.

Currently, the program does not have a GUI; to run the program, download the zip file and run the separate sections individually. Epochs and validation frequency are variables that can be adjusted for a variance in accuracy.

## Project Status

This project is in development. At the time of this update, it has an accuracy rate of 56.67% and successfully labeled the example images. Despite an increase in epochs and validation frequency, it seems to stagnate at 56.67%; this could be a limitation of the small dataset. Going forward, processing a larger dataset (in particular, the Curated Breast Imaging Subset of Digital Database for Screening Mammography) is the next step, with the aim of achieving a higher accuracy rate.

## Dataset Citation

Suckling, J., Parker, J., Dance, D., Astley, S., Hutt, I., Boggis, C., Ricketts, I., Stamatakis, E., Cerneaz, N., Kok, S., Taylor, P., Betal, D., & Savage, J. (2015). Mammographic Image Analysis Society (MIAS) database v1.21. Apollo - University of Cambridge Repository. 
https://doi.org/10.17863/CAM.105113

## Acknowledgement
Special thanks to Dr. David Ferry for valuable insights and guidance throughout this project!
At the time of this update, the training settings are referenced from Matlab examples.
