# Custom CNN-ViT & CNN for seizure detection using ECG Spectrograms (Reusable for Image Classification)

This repository contains **my custom-designed CNN-ViT and CNN architectures** for detecting seizures from ECG spectrograms.  
While designed for ECG data, the models are **fully adaptable for other image classification tasks**, making them reusable beyond this project.

---

## Process

1. A customized dataset is built for PyTorch
2. A patient independent 5-fold cross-validation is conducted in PyTorch to train the models using the train and validation datasets and then test them on the unseen test set 
4. Different measures, such as confusion matrix, AUC, Accuracy, MCC, and F1 Score, were used to evaluate the model's performance

---
CNN-ViT architecture is illustrated below:

![Model Architecture](cnnvit.png)


CNN architecture is illustrated below:

![Model Architecture](CNNmodel_seizure.png)

---
## Citation
All results and detailed information are available in my paper "Investigating the Applicability of ECG Signals for Neonatal Seizure Detection Using ECG Spectrograms and CNN-ViT" 
which was presented at the Biosignals conference, 2026. 
>Available at: https://www.scitepress.org/Papers/2026/143263/143263.pdf

``` bash
@article{rezaei2026investigating,
  title={Investigating the Applicability of ECG Signals for Neonatal Seizure Detection Using ECG Spectrograms and CNN-ViT},
  author={Rezaei, Kimia and Mathieson, Sean R and Lightbody, Gordon and Boylan, Geraldin B and Marnane, William P},
  year={2026}
}
```
---

## Installation

1. Clone the repository:
```bash
git clone https://github.com/kimiarezaei/Custom-CNN-ViT-and-CNN-Architectures-for-Seizure-Detection-Adaptable-to-Image-Tasks-.git
cd Custom-CNN-ViT-and-CNN-Architectures-for-Seizure-Detection-Adaptable-to-Image-Tasks-
