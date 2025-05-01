 # Digital_Image_Processing_Project
# 🎬 Color Scheme-Based Genre Detection and Movie Recommendation

This project explores the correlation between movie color schemes and their genres, using image processing and machine learning. It extracts dominant color palettes from movie frames or posters, classifies the genre, and recommends similar movies accordingly.

## 🔍 Features

- 🎨 Extract dominant color schemes from movie posters or frames
- 🧠 Predict movie genres using machine learning models
- 🤖 Recommend similar movies based on color similarity and genre
- 📊 Visualization of color palettes for analysis
- 🗂️ Dataset creation and preprocessing tools

---


## ⚙️ How It Works

1. **Color Scheme Extraction**
   - Uses `k-means clustering` and `sub hull segmentation` to identify dominant colors in the entire movie/movie trailer .
   - Palettes are stored and used as features.

2. **Genre Classification**
   - Trained ML model takes color features and predicts the movie genre.

3. **Recommendation Engine**
   - Based on predicted genre and color similarity using cosine similarity and k-NN.

---

## 📦 Installation

1. Clone the repo
2. Run the ipynb in your system locally or simply in colab/jupyter.

## 📊 Dataset
You can create your own dataset using:

1. Public movie poster datasets 
2. Frame extraction from trailers using ffmpeg

## 🛠️ Built With
Python,OpenCV , PIL , scikit-learn, matplotlib , seaborn
