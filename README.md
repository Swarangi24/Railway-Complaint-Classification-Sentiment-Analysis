# Railway-Complaint-Classification-Sentiment-Analysis

A Machine Learning-powered web application for handling and classifying railway-related complaints using text sentiment analysis and image classification. This system helps automate the categorization and prioritization of complaints for efficient resolution by the respective departments.

---

## 🚀 Features

- **Sentiment Analysis** using SGD Classifier (76% accuracy)
- **Image Classification** with DenseNet201 for detecting complaint types
- **Department-wise Classification** using Gradient Boosting
- Real-time complaint submission and tracking
- Admin dashboard for complaint monitoring and filtering
- Structured data storage with MySQL
- Built with Flask and Python for the backend

---

## 🛠 Tech Stack

- **Frontend:** HTML, CSS, Bootstrap
- **Backend:** Flask (Python)
- **ML Models:**
  - SGD Classifier for Sentiment Analysis
  - DenseNet201 for Image Classification
  - Gradient Boosting for Department-wise Categorization
- **Database:** MySQL
- **Libraries:** Scikit-learn, TensorFlow/Keras, OpenCV, Pandas, NumPy

---

## 🔍 How It Works

1. **User Submission**  
   Users register and submit complaints with text descriptions and optional images.

2. **Machine Learning Models**  
   - Text is classified for sentiment using the SGD Classifier.  
   - Images are analyzed using DenseNet201 to identify the category of issue.  
   - Complaint is routed using a Gradient Boosting model to the relevant department.

3. **Admin Handling**  
   Admin panel displays categorized and prioritized complaints, enabling faster resolution.

---
