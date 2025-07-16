# 🤖 ANN-Classification (Extended with Regression & Logging)

Welcome to the **Artificial Neural Network (ANN) Classification & Regression Project**! This repository contains end-to-end implementations of ANN models for **customer churn classification** and **salary regression**, along with comprehensive experiment tracking and a Streamlit app for model deployment.

---

## 🚀 Project Overview

This project demonstrates practical applications of Artificial Neural Networks (ANNs) for:

- **Customer Churn Prediction** 🔄 (Classification)  
- **Salary Prediction** 💰 (Regression)

Both models are built using TensorFlow/Keras and include preprocessing pipelines, hyperparameter tuning, and detailed training logs compatible with TensorBoard.

---

## 📁 Repository Structure

├── logs/                       📊 TensorBoard logs for classification training & validation  
├── regressionlogs/             📉 TensorBoard logs for regression training & validation  
├── app.py                     🌐 Streamlit app to serve the trained classification model  
├── Churn_Modelling.csv         🗃️ Dataset for customer churn prediction  
├── experiments.ipynb           📓 ANN classification model experiments & training  
├── hyperparametertuning.ipynb  ⚙️ Hyperparameter tuning for ANN models  
├── label_encoder_gender.pkl    🔤 Gender label encoder for preprocessing  
├── model.h5                   💾 Saved Keras ANN classification model  
├── onehot_encoder_geo.pkl      🌍 One-hot encoder for geographic feature  
├── prediction.ipynb            🔮 Making predictions with the trained classification model  
├── README.md                   📄 This file  
├── regression_model.h5         💾 Saved Keras regression model for salary prediction  
├── requirements.txt            📦 Python dependencies  
├── salaryregression.ipynb      📓 Salary regression experiments and model training  
├── scaler.pkl                  ⚖️ Feature scaler for preprocessing  
├── .gitignore                  🚫 Files/folders excluded from git  

---

## 🧰 Technologies & Libraries

- 🐍 Python 3.x  
- ⚙️ TensorFlow & Keras  
- 🐼 Pandas, NumPy  
- 🎛️ Scikit-learn (for preprocessing)  
- 🌐 Streamlit (for app deployment)  
- 📊 TensorBoard (for logging & visualization)  
- 📦 Pickle (for saving preprocessing objects)  

---

## ⚙️ Setup Instructions

1. **Clone the repository:**  
   `git clone https://github.com/Aparna-k246/ANN-Classification.git`  
   `cd ANN-Classification`

2. **Create a virtual environment (optional but recommended):**  
   `python -m venv venv`  
   `source venv/bin/activate`      # On Windows: `venv\Scripts\activate`

3. **Install dependencies:**  
   `pip install -r requirements.txt`

4. **Run Jupyter notebooks** to explore experiments and predictions:  
   `jupyter notebook`

5. **Start the Streamlit app** to serve the classification model:  
   `streamlit run app.py`  
   The app will be available at `http://localhost:8501`

---

## 📊 Usage Highlights

- 🛠️ **Data preprocessing:** Categorical features (gender, geography) are encoded using saved encoders (`.pkl` files). Numerical features are scaled for optimal ANN performance.  
- 🧠 **Model training:** ANN architectures with hyperparameter tuning for best performance.  
- 📈 **Logging:** Training metrics logged for both classification and regression using TensorBoard.  
- 🚀 **Deployment:** `app.py` runs a Streamlit app to provide an interactive UI for real-time predictions.

---

## 📈 TensorBoard Visualization

To monitor model training and validation metrics in real-time, run:  
`tensorboard --logdir logs/`

For regression logs, use:  
`tensorboard --logdir regressionlogs/`

Open `http://localhost:6006` in your browser to visualize metrics such as loss and accuracy.

---

## 🎯 Potential Improvements

- ✅ Add unit tests for preprocessing and app endpoints.  
- 📊 Expand regression models for other salary datasets.  
- 🐳 Containerize the Streamlit app using Docker for easier deployment.  
- 🤖 Integrate CI/CD pipelines for automated testing and deployment.

---

## 💼 Recruiter & Collaborator Section

If you’re a recruiter, hiring manager, or collaborator interested in machine learning, AI, or data science projects, here’s why this repo matters:

- Proven skills in building and deploying deep learning models 🔥  
- Experience with end-to-end ML pipelines including data preprocessing, modeling, and deployment 🚀  
- Familiarity with modern tools: TensorFlow, Streamlit, TensorBoard, and more 💻  
- Ability to tune and optimize models for performance 📈  
- Hands-on with building user-friendly ML applications for real-world business problems 🎯  

**Feel free to contact me for opportunities or collaborations!**

---

## 📞 Contact & Connect

- **GitHub:** [Aparna-k246](https://github.com/Aparna-k246)  
- **LinkedIn:** [linkedin.com/in/aparna-k-628005167](https://www.linkedin.com/in/aparna-k-628005167/)  
- 📧 Email: [Add your email here]

---

## ⭐️ If you find this project useful, please consider starring ⭐️

---

Thanks for visiting! 🙌  
Happy Coding & Modeling! 🚀
