# Handwritten Digit Recognition using CNN

A deep learning project that classifies handwritten digits (0–9) using a Convolutional Neural Network (CNN) trained on the MNIST dataset. This project demonstrates the complete workflow of data preprocessing, model design, training, evaluation, and deploying predictions through a simple GUI.

---

## 🚀 Features
- CNN-based handwritten digit classifier
- Preprocessing pipeline (normalization, reshaping, one-hot encoding)
- Achieved over **97% validation accuracy**
- Real-time digit prediction using a GUI drawing interface
- Custom forward propagation and prediction using saved model weights
- Simple scripts for training and testing

---

## 📂 Project Structure
```bash
Handwritten_digit_recognition_CNN/
│
├── main.py               # Data loading, training, evaluation
├── Model.py              # CNN model architecture
├── Prediction.py         # Prediction functions
├── RandInitialize.py     # Random weight initialization
├── GUI.py                # GUI for drawing digits
│
├── Theta1.txt            # Saved weights (Layer 1)
├── Theta2.txt            # Saved weights (Layer 2)
├── mnist-original.mat    # MNIST dataset
├── requirements.txt      # Dependencies
└── __pycache__/          # Cache files 
```


## ⚙️ Technologies Used
- Python  
- TensorFlow / Keras  
- NumPy  
- Matplotlib  
- Tkinter  
- MNIST Dataset  

## 🧠 Model Architecture
- Input: 28×28 grayscale images  
- Hidden Layer 1: Dense + ReLU  
- Hidden Layer 2: Dense + ReLU  
- Output Layer: Softmax (10 classes)  
- Optimizer: Adam  
- Loss Function: Categorical Crossentropy  


## 📥 Dataset
This project uses the **MNIST** dataset containing:
- 42,000+ labeled digit images  
- 28×28 pixel grayscale format  
- Training and test splits included  


# 📌 How to Run the Project

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/YourUserName/Handwritten_digit_recognition_CNN.git
cd Handwritten_digit_recognition_CNN
python -m venv env
source env/bin/activate   # Mac/Linux
env\Scripts\activate      # Windows
pip install -r requirements.txt
python main.py
python Prediction.py
python GUI.py
```

## 📸 Output Screenshot
![Screenshot 2025-11-19 134233](https://github.com/user-attachments/assets/95164842-846d-4f51-954e-cebf35066cdb)
![Screenshot 2025-11-19 134115](https://github.com/user-attachments/assets/8aa1f73e-3c6e-41ca-840c-dde7b76ce133)
![Screenshot 2025-11-19 132330](https://github.com/user-attachments/assets/9b153e65-af3b-47d0-97af-5bfea1fef0d8)

