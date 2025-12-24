# 📸 Image Retrieval System

## 🔍 Overview
This project implements a Content-Based Image Retrieval (CBIR) system that retrieves visually similar images from a dataset based on a query image. Instead of relying on text or labels, the system compares images using deep visual features extracted from a Convolutional Neural Network.

---

## 🧠 Core Idea
1. Extract deep features from images using a pretrained ResNet model  
2. Store feature vectors for all dataset images  
3. Extract features from a query image  
4. Compute similarity using KNN / cosine / Euclidean distance  
5. Retrieve the most visually similar images  

---

## 🛠️ Tech Stack
- Python  
- PyTorch  
- ResNet (CNN)  
- NumPy  
- scikit-learn  
- Gradio  
- Jupyter Notebook  

---

## 📂 Project Structure

---

## ⚙️ How It Works
- Images are passed through a pretrained ResNet network
- The final classification layer is removed
- The output vector represents semantic image features
- Similarity is computed using distance-based methods
- Top-K similar images are returned

---

## 🚀 How to Run
Install dependencies:

Run the UI:

---

## 📊 Experiments
- CIFAR-10 image retrieval
- PCA + KNN analysis
- Feature similarity comparison

---

## ✅ Key Learning Outcomes
- CNN-based feature extraction
- Similarity search in high-dimensional space
- End-to-end deep learning project design
- ML model + UI integration

---

## 🔮 Future Improvements
- Larger datasets
- Faster search (FAISS)
- Model fine-tuning
- Deployment

---

## 👤 Author
Yash Chhaparwal  
B.Tech, LNMIIT Jaipur  

⭐ If you find this project useful, feel free to star the repository!
