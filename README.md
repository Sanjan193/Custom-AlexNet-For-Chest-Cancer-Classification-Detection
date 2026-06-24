# Custom-AlexNet-For-Chest-Cancer-Classification-Detection
This repository contains a PyTorch-based deep learning project for lung cancer classification using a custom-built AlexNet architecture, including data preprocessing, model training, and performance evaluation and got ~ 86 % accuracy and a 0.92+ Recall score.

# 🖼️ Model Architecture
<p align="center"> <img src="Plots/Custom_Alexnet.png" width="750"> </p>

# 📂 Dataset
   Dataset Source
   Kaggle Dataset:
   [https://www.kaggle.com/datasets/mohamedhanyyy/chest-ctscan-images]
| Classes                   | Description             |
| ----------------------- | ----------------------- |
| Adenocarcinoma          | Adenocarcinoma[a] (AC) is a type of cancer made of cells from glands. They can occur in many parts of the body. Adenocarcinomas are part of the larger grouping of carcinomas, but are also sometimes called by more precise terms, omitting the word when these exist. Adenocarcinomas are defined as neoplasia of epithelial tissue that has a glandular origin or glandular characteristics. Thus, invasive ductal carcinoma, the most common form of breast cancer, is adenocarcinoma, although the term is not used in its name.     |
| Squamous Cell Carcinoma | Squamous-cell carcinoma (SCC), also known as epidermoid carcinoma, comprises a number of different types of cancer that begin in squamous cells.[1] These cells form on the surface of the skin, on the lining of hollow organs in the body, and on the lining of the respiratory and digestive tracts. |
| Large Cell Carcinoma    | Large-Cell Lung Carcinoma (LCLC), or Large-Cell Carcinoma (LCC) in short, is a heterogeneous group of undifferentiated malignant neoplasms that lack the cytology and architectural features of small cell carcinoma and glandular or squamous differentiation.[1] LCC is categorized as a type of NSCLC (non-small-cell lung carcinoma) that originates from the epithelial cells of the lung. LCLC is histologically characterized by the presence of large, undifferentiated cells that lack distinctive features of either squamous cell carcinoma or adenocarcinoma (other types of cancers). Typically seen in LCLC, tumor cells have abundant pale-staining cytoplasm and prominent nucleoli.     |
| Normal                  | Healthy lung tissue     |

## Accuracy Curve
<p align="side"> <img src="Plots/Accuracy.png" width="400"> </p>








## 📂 Repo Structure

```text
Custom-alexnet-For-Chest-Cancer-Classification/
│
├── models/
│   └── Gdrive_link/
│
├── Notebook/
│   └── Chest_Cancer(AlexNet).ipynb
│
├── Plots/
|   |── Accuracy.png
|   ├── Custom_Alexnet.png
|   └── Loss_curve.png
|
├── dataset_link/
├── LICENCE
├── requirements.txt
|── README.md
```
