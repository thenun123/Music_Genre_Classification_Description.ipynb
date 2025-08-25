# 🎶 Music Genre Classification 🎧

This project explores different approaches to classify music genres using the **GTZAN dataset**.  
Both **machine learning on audio features** and **deep learning on spectrogram images** are implemented to compare performance.  

---

## 💾 Dataset
- **GTZAN Dataset** (downloaded from Kaggle via `kagglehub`)  
- Contains:  
  - **Audio files**  
  - **Pre-extracted features** (`features_30_sec.csv`)  
  - **Spectrogram images**  

---

## ✨ Approaches

### 1. Machine Learning on Audio Features  
- Loaded and preprocessed audio features from `features_30_sec.csv`.  
- Scaled features using **StandardScaler**.  
- Split dataset into training and testing sets.  
- Trained the following models:  
  - **Random Forest** 🌲  
  - **Logistic Regression** 📈  
  - **K-Nearest Neighbors (KNN)** 🏘️  
- Compared performance using **accuracy** and **confusion matrices**.  

### 2. Deep Learning on Spectrogram Images  
- Loaded spectrogram images from the dataset.  
- Visualized sample spectrograms.  
- Built and trained a **Convolutional Neural Network (CNN)** using **TensorFlow/Keras** 🧠.  
- Evaluated performance on the test set.  
- Plotted training and validation **accuracy** and **loss** over epochs 📊.  

---

## 📊 Results
- **Machine Learning models** achieved varying accuracy across genres, with confusion matrices highlighting strengths and weaknesses.  
- **CNN model** trained on spectrograms showed promising results with clear genre separation.  
- Plots of training history provide insights into model convergence and potential overfitting.  

---

## 🚀 How to Run
1. Ensure you have a **Kaggle account** and accept the dataset's terms of use.  
2. Install required libraries:  
   ```bash
   pip install kagglehub pandas scikit-learn tensorflow matplotlib opencv-python
