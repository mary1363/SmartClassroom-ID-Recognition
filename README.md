
# 🧠 Smart Classroom: Handwritten Student ID Recognition

This project demonstrates how machine learning can be applied in education to automatically recognize handwritten student ID numbers, helping teachers manage classrooms efficiently.

---

## 🎯 Objective
To build a Smart Classroom System that:
- Automatically identifies students by their handwritten ID.
- Displays the recognized ID on a teacher dashboard.
- Reduces manual attendance work and improves classroom interaction.

---

## 🧩 Dataset
- MNIST Handwritten Digit Dataset
- Training samples: 60,000  
- Testing samples: 10,000  
- Each image: 28×28 grayscale handwritten digit
- The MNIST dataset files used in this project can be downloaded here:

- [MNIST_train.csv](https://docs.google.com/spreadsheets/d/1aOZXH_mpK5yOApDcEC3BunVp5jwT0ZKw/edit?usp=drive_link&ouid=115813122716964597664&rtpof=true&sd=true)
- [MNIST_test.csv](https://docs.google.com/spreadsheets/d/1tCm8YnSLx6MCGpmuiHwr4KlndRwtxA6e/edit?usp=drive_link&ouid=115813122716964597664&rtpof=true&sd=true)

---

## ⚙️ Models Implemented
1. Gaussian Naive Bayes – assumes feature independence, very fast but lower accuracy.  
2. Non-Naive Gaussian Bayes – includes feature variance and covariance, higher accuracy.  
3. K-Nearest Neighbors (KNN) – classifies digits based on distance, performs best when tuned.

---

## 🔧 Preprocessing & Tuning
- Scaling: Normalized pixel values for better model convergence.  
- Epsilon tuning: Improved Gaussian model accuracy up to 94%.  
- Blurring: Reduced noise and enhanced KNN performance to 96%.  

---

## 📊 Results
| Model | Accuracy (%) | Notes |
|--------|---------------|-------|
| Gaussian Naive Bayes | 77 | After scaling |
| Non-Naive Gaussian Bayes | 94 | After epsilon tuning |
| KNN | 95–96 | After tuning & blurring |

---

## 🚀 Tools & Libraries
- Python, NumPy, Pandas, Matplotlib
- Google Colab for training and testing
- MNIST Dataset (CSV format from Kaggle)

---

## 🧠 Use Case: Smart Classroom
Students write their ID numbers →  
Machine learning model recognizes digits →  
Teacher dashboard displays each student's ID in real-time.

Benefits:
- ⏱️ Saves time by automating attendance  
- 👩‍🏫 Real-time feedback for teachers  
- 💡 Demonstrates how ML enhances education

---

## 📎 Author
Maryam Jafarian  
Data Scientist in ITC  

---

## 💬 Citation / Reference
MNIST Dataset — Yann LeCun, et al.  
