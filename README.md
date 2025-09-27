# sms-spam-detection--icail-
# 📱 SMS Spam Detection Using AI  
*Protecting users from digital threats through AI*

## 🚀 Project Overview
This project focuses on building an intelligent, lightweight spam detection model that automatically classifies SMS messages as **Spam** or **Ham (legitimate)**. With the rise of phishing and scam attempts through SMS, this solution aims to enhance digital safety for everyday users.

The project was developed as part of a final course project and successfully discussed and passed.  

## 🎯 Objectives
- Detect and filter out spam SMS messages effectively.  
- Raise awareness of SMS-based scams and digital threats.  
- Build a **fast, small-scale, and explainable model**.  
- Demonstrate the power of machine learning in text classification.  

## 👥 Team Members
- Ahmed Salah Ebrahim  
- Walaa Fathy  
- Mohamed Hamza  
- Nehal Sameh  
- Abdelrahman Atef  

## 🛠️ Tools & Technologies
- **Language:** Python  
- **Environment:** Google Colab  
- **Libraries:**  
  - `pandas` – data handling  
  - `scikit-learn` – TF-IDF, Naive Bayes classifier  
  - `TensorFlow` & `Keras` – deep learning experiments  

## 📊 Datasets
1. **Custom Dataset**  
   - 200 messages (100 Ham, 100 Spam)  
   - Balanced, preprocessed, realistic SMS samples  

2. **SMS Spam Collection (Kaggle)**  
   - 5,574 labeled messages  
   - Widely used benchmark dataset  

## 🔑 Key Features
- Efficient spam detection with high accuracy  
- Fully automated message classification  
- Lightweight, interpretable, and fast to train  
- Scalable to larger datasets  

## 🧪 Model & Results
- **Baseline Model:** Multinomial Naive Bayes  
  - Achieved **~99% accuracy** on small custom dataset  
- **Deep Learning Attempt:** Lightweight Neural Network (Tokenization + Embedding + GlobalAveragePooling1D)  
  - Competitive results on larger dataset  
- Outcome: Naive Bayes proved optimal for small-scale SMS data, while NN showed potential with more data.  

## 📌 Final Outcome
✅ A functional AI model that accurately classifies SMS messages into Spam or Ham.  
✅ Protects users from phishing and scam attempts by flagging suspicious messages.  
✅ Creates a safer, more organized communication environment for individuals and small businesses.  

## 🔮 Future Work
- Train with larger and more diverse datasets  
- Add a user interface (mobile or web app)  
- Deploy for real-time message detection  
- Compare performance with Logistic Regression, SVM, and Transformer-based models  

## 📂 Repository Contents
- `SMS_Spam_Detection_model.ipynb` → source code (training, evaluation, experiments)  
- `G3.pptx` → presentation slides (overview & results)  
- `README.md` → project documentation  

