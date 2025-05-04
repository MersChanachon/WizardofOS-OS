# 🎧 WizardofOS-OS: Mood Detection Using Deep Learning

Detect human moods from audio using deep learning!  
This project implements a Keras/TensorFlow-based model to classify emotions from audio clips, complete with memory profiling and performance evaluation.

---

## 📂 Dataset

👉 [Download the dataset here](https://drive.google.com/drive/folders/1cBCoxofrI9ymGLgaSakP9gTMPw5ANlFM?usp=drive_link)  

> **Note:**  
> - Unzip the file after downloading.  
> - Update the dataset path in the notebook accordingly.

---

## 🧠 Features

✅ Mood/Emotion classification using deep learning (Keras/TensorFlow)  
✅ Preprocessing, training, and evaluation pipelines  
✅ Confusion matrix and classification report for model performance  
✅ Real-time memory usage profiling during training  
✅ Fully compatible with **Google Colab**

---

## 📒 Project Structure
📁 WizardofOS-OS

┣ 📂 dataset.zip # Zipped audio dataset

┣ 📓 Mood_Detection.ipynb # Main Colab notebook

┗ 📄 README.md # Project overview


---

## 🛠️ Setup Instructions

1. **Install required packages:**
   ```bash
   !pip install memory_profiler
2. **Mount Google Drive (in Colab):**
    ```bash
    from google.colab import drive
    drive.mount('/content/drive')
3. **Extract the dataset:**
    ```bash
    !unzip "/content/drive/MyDrive/your_dataset_path/dataset.zip" -d "/content/dataset"
4. **Run Mood_Detection.ipynb step by step**

