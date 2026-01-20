## 🌍 Language Detection App (RNN + Streamlit)

- A Language Detection Web Application built using a Recurrent Neural Network (RNN) and deployed with Streamlit.
The application predicts the language of a given sentence along with a confidence score.

- This project demonstrates an end-to-end NLP + Deep Learning workflow, including EDA, model training, inference, and deployment.

## 🚀 Features

- Predicts the language of input text

- Built using RNN (TensorFlow / Keras)

- Clean and interactive Streamlit UI

- Displays prediction confidence

- Modular and deployment-ready codebase

## 📁 Project Structure

.
├── app.py
├── simple_rnn_model.h5
├── tokenizer.pkl
├── requirements.txt
├── prediction.ipynb
├── eda.ipynb
├── .gitignore
└── README.md

## ⚠️ Important
For Streamlit Cloud or production deployment:

saved_model/
├── simple_rnn_model.h5
└── tokenizer.pkl

## 🧠 Model Information

- Model Type: Simple Recurrent Neural Network (RNN)

- Framework: TensorFlow / Keras

- Text Processing: Tokenization + Padding

- Max Sequence Length: 80

- Output: Language class probabilities

## 🛠️ Tech Stack

- Python

- TensorFlow / Keras

- NumPy

- Pandas

- Scikit-learn

- Streamlit

## ▶️ Run the App

```bash
streamlit run app.py
```

## 👨‍💻 Author & Contact

- Ayush Raj
- AI / Machine Learning Enthusiast

📧 Email: ayushraj2004a@gmail.com

🐙 GitHub: https://github.com/ayushraj-aiml

💼 LinkedIn: https://www.linkedin.com/in/ayush-raj-906063230/

## ⭐ Acknowledgements

- TensorFlow & Keras Team

- Streamlit Community