# Image-Classification-with-SVM-Cats-vs-Dogs

This project implements a **Support Vector Machine (SVM)** to classify images of cats and dogs using the popular **Cats vs Dogs** dataset from Kaggle.
The aim is to use traditional machine learning techniques (without deep learning) to build a binary image classifier by extracting useful features from images and training an SVM model.
Built an SVM-based image classifier to distinguish between cats and dogs using the Kaggle dataset. Preprocessed image data, extracted HOG features, and trained a Support Vector Machine achieving high accuracy without deep learning. Tools used: Python, scikit-learn, OpenCV.


---

## 🧠 Objective

To classify images into two categories — **cats** and **dogs** — using an SVM model trained on extracted features from the raw image data.

---

## 📦 Project Workflow

1. **Data Preparation**
   - Load images from the Kaggle Cats vs Dogs dataset
   - Resize and convert to grayscale or flatten RGB images
   - Label encoding (cat = 0, dog = 1)

2. **Feature Extraction**
   - Use raw pixel data or extract HOG (Histogram of Oriented Gradients) features

3. **Model Building**
   - Train an SVM classifier using scikit-learn
   - Evaluate using accuracy, confusion matrix, and classification report

4. **Visualization**
   - Show sample predictions
   - Plot confusion matrix

---

## 🛠️ Tools & Technologies

- Python  
- scikit-learn  
- NumPy, Pandas  
- Matplotlib, Seaborn  
- OpenCV or PIL (for image handling)

---

## 🗂️ Dataset

- **Dataset**: [Dogs vs. Cats | Kaggle](https://www.kaggle.com/competitions/dogs-vs-cats/data)  
- Contains 25,000 labeled images (cats and dogs)

---

## 📊 Results

- Achieved high accuracy using handcrafted features and a linear/kernel SVM  
- Demonstrated the use of traditional ML techniques in image classification without deep learning

---

## ✅ Future Enhancements

- Compare performance with deep learning models (e.g., CNNs)
- Try dimensionality reduction (PCA)
- Deploy with Streamlit for interactive prediction

---

## 📁 Project Structure

