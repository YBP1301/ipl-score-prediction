# 🏏 IPL Score Prediction using Deep Learning

[![Made with Python](https://img.shields.io/badge/Made%20with-Python-blue.svg)](https://www.python.org/)
[![Platform - Colab](https://img.shields.io/badge/Platform-Google%20Colab-yellowgreen)](https://colab.research.google.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

---

## 📌 Overview

This project uses Deep Learning techniques to **predict the final score of an IPL match** based on real-time inputs like runs, wickets, overs, and current run rate.

Built using `Keras` and `TensorFlow`, it’s designed to assist in **cricket match analytics and live score projections**.

---

## 🧰 Tech Stack

- Python 🐍
- Pandas, NumPy
- Matplotlib & Seaborn (Visualization)
- Keras (Deep Learning)
- scikit-learn (Preprocessing, Model Evaluation)
- ipywidgets (Interactive UI)

---

## 📂 Dataset

The dataset is sourced from **Kaggle IPL matches data**, which includes ball-by-ball match stats like:
- Batting team
- Bowling team
- Current score, wickets
- Overs, last 5 overs run rate

---

## 🧠 Model Architecture

- Preprocessing done using Label Encoding and feature scaling
- Trained a Sequential Deep Learning Model using Keras
- Optimized using Adam optimizer and Mean Squared Error loss function
- Trained on match data with 3 hidden layers and dropout to prevent overfitting

---

## 🎮 Features

- Interactive input using `ipywidgets` to allow real-time scenario testing
- Predicts the final score dynamically
- Visualization of model training performance (loss & accuracy graphs)

---

## 🔧 How to Run

You can open this notebook directly on Google Colab:  
👉 **[Open in Colab](https://colab.research.google.com/)**

1. Upload the dataset
2. Run each cell in sequence
3. Use the interactive widget to test different match scenarios

---

## 🙋‍♂️ Author

Made with ❤️ by **Prateek (YBP1301)**  
Feel free to connect on [LinkedIn]https://www.linkedin.com/in/prateek-y-b-972ab423b?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app or explore more of my work!

---

## 📄 License

This project is licensed under the MIT License.
