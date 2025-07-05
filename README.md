# ANN-Classification-Customer-Churn-Prediction
Built an Artificial Neural Network (ANN) model to predict customer churn for a bank, helping identify customers at risk of leaving the bank. The model aids in designing targeted customer retention strategies and improving business decision-making.

## 🛠️ Tech Stack

- Python
- Pandas, NumPy
- TensorFlow / Keras (ANN)
- Scikit-learn
- Streamlit
- Matplotlib / Plotly

## ✨ Features

- Predicts customer churn (Yes/No) using a trained ANN
- Real-time prediction via Streamlit UI
- Accepts manual input or CSV file upload
- Displays prediction result, probability score, and visual insights
- Clean interface for business analysts and developers

## ⚙️ How It Works

1. Load and clean the dataset (e.g., from Telco or Kaggle).
2. Encode categorical features and scale numerical values.
3. Define and train an ANN model using TensorFlow/Keras:
   - Input Layer
   - Hidden Layers (with ReLU activation)
   - Output Layer (with Sigmoid activation)
4. Evaluate the model on test data.
5. Save the model and deploy with Streamlit for user interaction.

## 🧩 Installation

```bash
git clone https://github.com/anshhuuu/customer-churn-ann.git
cd customer-churn-ann
pip install -r requirements.txt
