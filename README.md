# Magnetic Tile Defect Classification (PyTorch)

This project trains a CNN to classify defects in magnetic tiles using the **Magnetic-Tile-Defect** dataset taken from Kaggle.

## Dataset

Dataset (not included in this repo) contains images of magnetic tiles with different defect types, for example:

- `MT_Free` – no defect
- `MT_Crack` – crack defects
- `MT_Fray` – fray defect
- `MT_Blowhole` (depending on the split) – blowhole defect

## Goals
- Learn how to build an end-to-end image classification pipeline in PyTorch.
- Work with real industrial defect detection data.
- Train a custom CNN and evaluate its performance.

##  Key steps in this Project
1. Data splitting into train/validation sets
2. PyTorch `ImageFolder` loaders
3. Data augmentation and normalization
4. CNN model (3 conv layers + FC layers)
5. Training and validation loop
6. Evaluation with confusion matrix, classification report
7. Plotting loss and accuracy curves

The images are organized into class folders and then split into:

```text
data/
  train/
    MT_Free/
    MT_Crack/
    MT_Fray/
    MT_Blowhole/
  val/
    MT_Free/
    MT_Crack/
    MT_Fray/
    MT_Blowhole/
