# PRODIGY_ML_03-
# 🐶🐱 PRODIGY_ML_03 – Cat vs Dog Image Classification using SVM

This project was completed as part of my **Machine Learning Internship** at **Prodigy InfoTech**.

---

## 📌 Task Objective

To implement a **Support Vector Machine (SVM)** model that classifies images of **cats and dogs** using image features from the **Kaggle Dogs vs Cats dataset**.

---

## 📂 Dataset

Used the **Dogs vs Cats** dataset from Kaggle:  
🔗 [Dogs vs Cats Dataset](https://www.kaggle.com/c/dogs-vs-cats/data)

- Contains 25,000 labeled images (12,500 cats + 12,500 dogs)
- Filenames: `cat.0.jpg`, `dog.0.jpg`, etc.

---

## ⚙️ Technologies Used

- Python
- NumPy
- OpenCV / PIL
- scikit-learn (SVC)
- Matplotlib
- Jupyter Notebook

---

## 🔍 Workflow

1. **Data Preprocessing**
   - Resized all images to 64×64
   - Converted to grayscale
   - Flattened into vectors for SVM input

2. **Labeling**
   - 0 = Cat, 1 = Dog (based on filename)

3. **Modeling**
   - Used `SVC(kernel='linear')` from `sklearn.svm`
   - Trained on 80% of the data, tested on 20%

4. **Evaluation**
   - Accuracy score
   - Classification report
   - Confusion matrix
   - Sample prediction visualization

---

## ✅ Result

The SVM model classified cat and dog images with good accuracy using basic image features.  
This task helped enhance my knowledge of **image preprocessing**, **SVM**, and **binary classification** using traditional ML techniques.

---

## 🔗 LinkedIn Post

👉 *[https://www.linkedin.com/in/saran-kumar-s-b45b75317/overlay/about-this-profile/?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base%3BMZmbrUDPRUyp9ruRsjBCsA%3D%3D]*

---

## 👨‍💻 Author

**Saran Kumar S**  
Machine Learning Intern – Prodigy InfoTech  
[GitHub Profile](https://github.com/Thunder371-hub) <!-- Replace this with your actual GitHub profile URL -->
