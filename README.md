#  Pneumonia Detection using CNN

A deep learning project that uses a **Convolutional Neural Network (CNN)** to classify chest X-ray images as **NORMAL** or **PNEUMONIA**.

##  Highlights

-  CNN-based image classification
-  Chest X-ray preprocessing and normalization
-  Training & validation performance
-  Classification report & confusion matrix
-  Interactive image upload for prediction
-  Prediction confidence score

##  Tech Stack

`Python` · `TensorFlow/Keras` · `NumPy` · `Matplotlib` · `Seaborn` · `Scikit-learn`

##  Dataset

The model uses a chest X-ray dataset organized into:

```text
chest_xray/
├── train/
├── val/
└── test/
    ├── NORMAL/
    └── PNEUMONIA/
```

### The dataset is not included in this repository.

## Run

 ``` bash pip install tensorflow numpy pandas matplotlib seaborn scikit-learn pillow jupyter ipywidgets
jupyter notebook pneumonia_detection_cnn.ipynb
```
## Disclaimer
This project is for educational and research purposes only and is not intended for medical diagnosis.

## Future Work
- Transfer learning
- Data augmentation
- Model optimization
- Web deployment
