# Plant Disease Detection Model

This repository contains a **trained machine learning model (`.h5`)** for **plant disease detection**.  
The model is intended for **prediction/inference only** and can be easily integrated into other applications or APIs.

---

## Model File

- **File:** `Smart_Farming_DL_Model.h5`
- **Framework:** TensorFlow / Keras
- **Purpose:** Predict plant diseases from input images
---

## Training Notebook

The complete **training pipeline** (data preprocessing, model architecture, training, and evaluation) is available as a public Kaggle notebook:

🔗 **Kaggle Notebook:**  
https://www.kaggle.com/code/muhammadumarfarooq0/plant-disease-detection

This notebook was used to train and generate the final `.h5` model.

---

## Usage (Inference)

```python
from tensorflow.keras.models import load_model

model = load_model("plant_disease_model.h5")
