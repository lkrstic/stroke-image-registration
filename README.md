# Stroke Image Registration with MONAI
### Lana Krstic
### CAP 6683 - AI in Medicine and Healthcare

This demo shows how to perform image registration using the MONAI Core framework. We load a set of MRI images showing ischemic stroke, then train a basic model. Each image is paired with a copy which undergoes a series of transformations. The system should then predict which transformations took place between the paired images, and align them accordingly.

The dataset used in this notebook is courtesy of the following paper:

B. Tasci, I. Tasci, Deep feature extraction based brain image classification model using preprocessed images: PDRNet, Biomedical Signal Processing and Control, 78 (2022) 103948. https://doi.org/10.1016/j.bspc.2022.103948

It was downloaded from https://www.kaggle.com/datasets/buraktaci/mri-stroke
