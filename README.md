# 🧠 Next Word Prediction using LSTM (RNN)

This project demonstrates a **Next Word Prediction** system built with **LSTM (Long Short-Term Memory)** — a type of Recurrent Neural Network (RNN).  
The app predicts the next possible word in a given sequence of words using a trained deep learning model.

---

## 🚀 Features
- Uses a **pre-trained LSTM model** for word prediction  
- Interactive **Streamlit web interface**  
- Accepts user input for any word sequence  
- Displays the predicted next word instantly  

---

## 🏗️ Tech Stack
- **Python 3.x**
- **TensorFlow / Keras** — for the LSTM model  
- **Streamlit** — for the user interface  
- **NumPy** — for data manipulation  
- **Pickle** — for loading the tokenizer  

---

## 📂 Project Structure
├── app.py # Streamlit app file

├── next_word_lstm.h5 # Trained LSTM model (required)

├── tokenizer.pickle # Tokenizer for word encoding (required)

└── README.md # Project documentation


---

## ⚙️ Installation & Setup

1. **Clone or download the repository**
   ```bash
   git clone https://github.com/yourusername/next-word-prediction.git
   cd next-word-prediction

2. **Install dependencies**
    ```bash
    pip install streamlit tensorflow numpy pickle-mixin
3.Run the Streamlit app

    streamlit run app.py


4. Open in your browser
  The app will run locally at:
  👉 http://localhost:8501

