# Created by Kunal Prasad
## 🗑️ Garbage Classification using EfficientNetV2B2
A deep learning project that classifies waste images into 6 recyclable categories using a hybrid CNN model built by fine-tuning EfficientNetV2B2 with custom Convolutional Neural Network layers. The project includes a web-based interface using Gradio with support for image upload and real-time webcam capture.

### Target Classes
    📦 Cardboard
    🧪 Glass
    ⚙️ Metal
    📄 Paper
    🧴 Plastic
    🚮 Trash
    
### ⚙️ Methodology

  - Image preprocessing (resizing, normalization) and data augmentation
  - Applied transfer learning with frozen base CNN layers
  - Trained models with EarlyStopping and ModelCheckpoint
  - Evaluated using accuracy/loss graphs and prediction samples

### 🛠️ Tools & Technologies Used

🐍 Python 3.x – Core programming language

📓 Jupyter Notebook – Interactive environment for writing and executing code

🧠 TensorFlow & Keras – Used for building, training, and evaluating the deep learning model

🧮 NumPy – For numerical operations

📊 Matplotlib & Seaborn – For data visualization (accuracy/loss graphs, confusion matrix)

🖼️ ImageDataGenerator (Keras) – For image preprocessing and real-time data augmentation

🧪 EfficientNetV2B2 – Pre-trained CNN used for transfer learning

📉 Scikit-learn – For generating classification report and confusion matrix
