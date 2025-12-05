# Magnetic Tile Defect Classification (PyTorch)

This project trains a convolutional neural network (CNN) to classify defects in magnetic tiles using the **Magnetic-Tile-Defect** dataset taken from Kaggle.

## Dataset

Dataset (not included in this repo) contains images of magnetic tiles with different defect types, for example:

- `MT_Free` – no defect
- `MT_Crack` – crack defects
- `MT_Fray` – fray defect
- `MT_Blowhole` (depending on the split) – blowhole defect

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
