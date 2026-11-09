# Eye Disease Classification with Deep Learning

Final project for the **Deep Learning** course (Spring 2025/2026), Al Hussein Technical University (HTU).

Cataracts, diabetic retinopathy and glaucoma are leading causes of preventable blindness. This project builds a computer-vision system that classifies retinal fundus images into four classes — **Cataract, Diabetic Retinopathy, Glaucoma and Normal** — using transfer learning in PyTorch.

## Contents

| File | Description |
|------|-------------|
| [Eye_Disease_Classification.ipynb](Eye_Disease_Classification.ipynb) | Full pipeline: data loading & augmentation, transfer learning with pretrained CNNs (ResNet-18, AlexNet), training, evaluation |
| [Deep-Learning-Technical-Report.pdf](Deep-Learning-Technical-Report.pdf) | Technical report: problem statement, theory, design, results and discussion |

## Results

Best model reached **≈ 85 % accuracy (F1 ≈ 0.84)** on the held-out test set. Models are compared on accuracy, precision, recall, F1 and confusion matrices.

## Dataset

[Eye Diseases Classification](https://www.kaggle.com/datasets/gunavenkatdoddi/eye-diseases-classification) on Kaggle (not included in this repo). The notebook was run on Google Colab and downloads the data with a Kaggle API token stored in your own Google Drive.

## Tech

Python · PyTorch · torchvision · scikit-learn · Matplotlib · Google Colab

---
**Author:** Hala Nazzal
