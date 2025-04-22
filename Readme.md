
```
# 🌿 Plant Disease Recognition System

A web-based application built with **Streamlit** and **TensorFlow** to detect plant diseases from leaf images. This model classifies images into 38 categories of plant diseases using a trained Convolutional Neural Network (CNN).

## 🚀 Features

- Upload leaf images for instant disease detection.
- CNN model trained on the "New Plant Diseases Dataset (Augmented)" from Kaggle.
- Clean, responsive web UI with real-time predictions.
- Hosted using **Vercel** serverless deployment.

## 🧠 Model

- Framework: TensorFlow / Keras
- Input size: 128x128 RGB images
- Trained on: 87,000+ labeled images
- Accuracy: ~94% on validation set

## 📂 Folder Structure
```
project-root/
├── api/
│   └── index.py                   # Main Streamlit app logic
├── trained_plant_disease_model.keras
├── home_page.jpeg
├── requirements.txt
├── vercel.json
└── README.md
```

## 📦 Setup Locally

```bash
pip install -r requirements.txt
streamlit run api/index.py
```

## 📊 Example Predictions

<img src="home_page.jpeg" alt="App Screenshot" width="400"/>

## 📚 Dataset Reference

- Kaggle: [New Plant Diseases Dataset (Augmented)](https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset)


---

Happy Plant Diagnosing! 🌱🔬
```
