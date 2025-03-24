# CancerGuardian 🎗️🔬

🚀 **CancerGuardian** is a machine learning-powered web application designed to assist in breast cancer diagnosis using the **Breast Cancer Wisconsin (Diagnostic) Dataset**. This tool predicts whether a tumor is **malignant** or **benign**, helping in early detection and decision-making.

---

## 🌟 Features
✅ Breast cancer classification using machine learning 📊  
✅ Trained on the **Breast Cancer Wisconsin (Diagnostic) Dataset** 🏥  
✅ Standardized input scaling with `StandardScaler` 🔄  
✅ Interactive web interface built with `streamlit` 🎨  
✅ Easy-to-run setup with pre-trained model 🎯  

---

## 📂 Project Structure
```
CancerGuardian/
│── assets/
│   └── style.css              # CSS for UI styling
│
│── dataset/
│   ├── data.csv               # Original dataset
│
│── model/
│   ├── data_cleaned.csv       # Processed dataset
│   ├── model.pkl              # Trained ML model
│   ├── scaler.pkl             # StandardScaler for input normalization
│   ├── train.py               # Script for training the model
│
│── app.py                     # Main application script
```

---

## 📊 Dataset Information
This project utilizes the **Breast Cancer Wisconsin (Diagnostic) Dataset**, available on Kaggle:
🔗 [Dataset Link](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)

The dataset contains **features extracted from digitized images of breast mass** and helps classify tumors into:
- **Malignant (cancerous) 🛑**
- **Benign (non-cancerous) ✅**

---

## 🛠️ Installation & Usage
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/ArchitJ6/CancerGuardian.git
cd CancerGuardian
```
### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```
### 3️⃣ Run the Application
```bash
streamlit run app.py
```

---

## 🏗️ How It Works
1️⃣ User inputs tumor-related features via the web interface 🖥️

2️⃣ Input is **standardized** using `StandardScaler` 📏

3️⃣ Pre-trained `model.pkl` predicts whether the tumor is **malignant** or **benign** 🧬

4️⃣ Result is displayed with an intuitive UI 🎨

---

## 🤝 Contributing
Contributions are welcome! Feel free to fork the repository, make improvements, and submit a pull request. 🚀

---

## 📜 License
This project is licensed under the [MIT License](LICENSE). 📜

---

## 🌟 Show Your Support
If you found this project helpful, ⭐️ **star the repository** and share it with others!

Happy coding! 💙