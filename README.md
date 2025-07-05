# 🗑️ Garbage Classification using EfficientNetV2B2
A deep learning project by Kunal Prasad

## 📌 Overview
This project classifies waste images into 6 recyclable categories using a hybrid CNN model. It utilizes EfficientNetV2B2 with custom layers through transfer learning. The model is trained on a labeled garbage dataset and evaluated for classification accuracy and performance.

🔧 This project is built in Jupyter Notebook and includes training visualization, model evaluation, and real-world sample predictions.

## ♻️ Target Classes
- 📦 Cardboard
- 🧪 Glass
- ⚙️ Metal
- 📄 Paper
- 🧴 Plastic
- 🚮 Trash

## ⚙️ Methodology
-  **Image preprocessing**: Resizing to 224×224, normalization
-  **Data augmentation**: Using ImageDataGenerator
-  **Transfer learning**: EfficientNetV2B2 with base CNN layers frozen initially
-  **Training**: Implemented EarlyStopping and ModelCheckpoint
-  **Evaluation**: Using accuracy/loss plots and confusion matrix

## 🛠️ Tools & Technologies Used
-  **Python 3.x**: Core programming language
-  **Jupyter Notebook**: Interactive environment for code development
-  **TensorFlow & Keras**: Deep learning framework
-  **NumPy**: Numerical operations
-  **Matplotlib & Seaborn**: Data visualization
-  **ImageDataGenerator (Keras)**: Real-time image preprocessing and augmentation
-  **EfficientNetV2B2**: Pre-trained CNN used for feature extraction
-  **Scikit-learn**: Classification reports and confusion matrix

## 🧠 What I Learned
-  **AI and Machine Learning Basics**: Gained foundational understanding of key concepts
-  **Image Dataset Handling**: Learned to preprocess and structure image data for classification
-  **CNN Model with Transfer Learning**: Built and trained a custom CNN using EfficientNetV2B2
-  **Model Evaluation**: Applied metrics and visualizations to assess and improve performance

##  Sample Outputs
-  **Training & validation accuracy/loss plots**
-  **Predicted labels on sample garbage images**
-  **Confusion matrix and classification report**

## 📂 Dataset Used
The dataset is sourced from Kaggle:
🔗 [Garbage Classification Dataset](https://www.kaggle.com/datasets/farzadnekouei/trash-type-image-dataset)

To use the dataset:
1. Download and unzip it.
2. Rename the folder to: `TrashType_Image_Dataset`
3. Place the folder inside the project directory.

## Getting Started
1. **Prerequisites**: Ensure you have Python, TensorFlow, and necessary libraries installed.
2. **Dataset**: Prepare the dataset as described above.
3. **Model Training**: Use the provided Jupyter Notebook to build and train the EfficientNetV2B2 model.
4. **Evaluation**: Analyze model performance using the provided scripts.

## Usage
- Clone this repository.
- Install dependencies: `pip install -r requirements.txt`
- Open the Jupyter Notebook: `jupyter notebook garbage_classification.ipynb`
- Follow the notebook to train and evaluate the model.

