# 👤 Influencer Face & Eye Classification  

A **Machine Learning project** for classifying selected influencers using **face and eye detection**. The model is trained only on specific influencers’ images, not general face recognition.  

---

## 📌 Project Overview  
- Used **Haar Cascade Classifier** to detect and crop faces/eyes.  
- Preprocessed images → converted into vectors for model training.  
- Applied **GridSearchCV** to find the best hyperparameters.  
- Final model: **Support Vector Machine (SVM)** with optimized parameters.  

---

## 🛠️ Tech Stack  
- Python, OpenCV (CascadeClassifier)  
- Scikit-learn (SVM, GridSearchCV)  
- NumPy, Pandas  

---

## 🔬 Workflow  
1. **Image Collection** → Few influencers only.  
2. **Face/Eye Detection** → Haar Cascade Classifier.  
3. **Preprocessing** → Crop, resize, flatten into vectors.  
4. **Model Selection** → GridSearchCV with SVM.  
5. **Best Parameters Found** → Used for final classification.  

---

## 📊 Results  
- Model successfully distinguishes selected influencers.  
- Optimized SVM improves accuracy compared to default parameters.  

---

## 👨‍💻 Author  
Developed by **[Your Name]** as a focused ML classification project.  
