# 🐶🐱 Dog vs Cat Classifier

A simple web-based image classifier built with **Flask** and **TensorFlow/Keras** that identifies whether an uploaded image is of a **dog** or a **cat**.

---

## 🚀 Features

- Upload any image (.jpg/.png)
- CNN model built using TensorFlow
- Web app powered by Flask
- Displays prediction (Dog or Cat) with confidence
- User-friendly interface

---

## 🧠 Model Details

- Trained on a dataset of dog and cat images
- Architecture: Convolutional Neural Network (CNN)
- Optimizer: Adam  
- Loss Function: Binary Crossentropy  
- Activation: ReLU & Sigmoid

---

## 📁 Folder Structure

dogVscat</br>
├── app.py # Flask backend </br>
├── model.h5 # Trained CNN model</br>
├── templates</br>
│ └── index.html # Frontend HTML</br>
├── static</br>
│ ├── style.css # CSS styling</br>
│ └── screenshot.png # Optional UI screenshot</br>
├── requirements.txt # Dependencies</br>
└── README.md # Project documentation</br>

---

## 🛠️ Installation & Run

### 🔧 Install Dependencies

```bash
pip install -r requirements.txt
```
python app.py
Then open http://127.0.0.1:5000/ in your browser.</br>
📸 Demo
<img width="1919" height="977" alt="image" src="https://github.com/user-attachments/assets/e817cd1b-23aa-4bf6-aa2a-b10216bda843" />

🧪 Example Prediction

Upload image →
✅ Output: This is a Cat!
🎯 Confidence: 92.5%

📦 Requirements

Example requirements.txt:

Flask
numpy
tensorflow
Pillow

To generate your own, run:

pip freeze > requirements.txt

💡 Future Improvements

    Add drag-and-drop image upload

    Improve prediction confidence display

    Add support for multiple image uploads

    Deploy to Render/Heroku

👩‍💻 Author

Agrima Chaturvedi
