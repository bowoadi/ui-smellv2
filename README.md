# UI Smell Detection with Few-Shot Learning

This repository contains the experimental notebook for the paper:

**Leveraging Few-Shot Learning for Automated Detection of UI Smells in Mobile UI Designs to Enhance Usability Evaluation**

## Authors
- **Aris Puji Widodo***  
  Department of Computer Science, Universitas Diponegoro, Indonesia  
  arispw@lecturer.undip.ac.id | ORCID: 0000-0003-4904-5034

- **Mohd Hanafi Ahmad Hijazi**  
  Creative Advanced Machine Intelligence Research Centre,  
  Universiti Malaysia Sabah, Malaysia  
  hanafi@ums.edu.my | ORCID: 0000-0003-0431-8967

- **Adi Wibowo**  
  Department of Computer Science, Universitas Diponegoro, Indonesia  
  bowo.adi@live.undip.ac.id | ORCID: 0000-0002-7966-1017

## Abstract
This study proposes a **few-shot learning framework** for automated detection of **UI smells** in mobile UI designs using screenshots.  
By leveraging the **Enrico dataset** and the **UI Smells Dataset**, visual features are extracted using CNN, MobileNet-V3, and EfficientNet (B0–B5), then classified using an **Adaptive Subspace Classifier** designed for few-shot scenarios.  
Experimental results show that **EfficientNet-B3** achieves the best performance with **90.14% accuracy** in a 5-shot setting.

## Keywords
Adaptive Subspace, Few-Shot Learning, Mobile UI Designs, UI Smell Detection, Usability Evaluation

## Dataset
- UI Smells Dataset (Kaggle):  
  https://www.kaggle.com/datasets/magiskaggle/ui-smells-dataset-separate

## File
- `ui-smell-fewshot-learning-2.ipynb` — main experimental notebook

## Notes
- Experiments are conducted in a few-shot learning setting.
- Dataset includes labeled mobile UI screenshots for UI smell detection.
