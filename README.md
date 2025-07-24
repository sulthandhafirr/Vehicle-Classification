# Vehicle Classification using Custom CNN

This project provides an AI-based solution to classify different types of vehicles using a custom-built Convolutional Neural Network (CNN). Built from scratch with TensorFlow and Keras, the model is trained to recognize seven vehicle categories and is designed to support smart transportation systems by enabling fast, automated, and accurate vehicle identification from images.

# Dataset

The dataset used in this project contains seven vehicle classes:
- `Auto Rickshaw`
- `Bike`
- `Car`
- `Motorcycle`
- `Plane`
- `Ship`
- `Train`

It can be downloaded directly from Kaggle using Kaggle API:

```python
!kaggle datasets download -d mohamedmaher5/vehicle-classification

import zipfile
with zipfile.ZipFile('vehicle-classification.zip', 'r') as zip_ref:
    zip_ref.extractall('dataset')
```

# Steps to Train

The training process is done using the notebook file: `VehicleClassification.ipynb`.

You can open this notebook in **Google Colab** or locally using Jupyter Notebook.

1. Open `VehicleClassification.ipynb`
2. Run each cell step by step
3. The dataset will be downloaded and extracted automatically
4. Model training will begin using the `train/`, `val/`, and `test/` directories
5. Accuracy and loss graphs will be displayed and saved in the `images/` folder

> **Tip**: It is recommended to use **Google Colab with GPU** for faster training and better performance.


# Output Example

After training, the results include:

- Classification accuracy on both training and validation datasets  
- Plotted loss and accuracy graphs  
- A trained CNN model capable of classifying 7 vehicle categories

# Credits

- Dataset: [Vehicle Classification – Kaggle Dataset](https://www.kaggle.com/datasets/mohamedmaher5/vehicle-classification)  
- Model: Custom CNN built using TensorFlow/Keras  
- Development: Google Colab  
- Visualization: Matplotlib  
- Image Preprocessing: Pillow (PIL)
- Deployment: Hugging Face Spaces + Gradio

Demo: https://huggingface.co/spaces/SulthanD/VehicleClassification

---

**Developed by: Sulthan Dhafir Rafief**
