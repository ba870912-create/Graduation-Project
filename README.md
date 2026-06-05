# 🍽️ FoodLens – AI-Powered Dietary Management System

FoodLens is an intelligent mobile application designed to assist individuals—especially those managing chronic conditions such as diabetes and hypertension—in making informed dietary decisions.

It leverages **Computer Vision, Deep Learning, and Nutritional Data Systems** to analyze meals from images and provide real-time, personalized dietary recommendations.

---

# 📌 Project Overview

FoodLens bridges the gap between medical dietary guidelines and real-world eating habits by enabling users to:

- Capture a photo of their meal  
- Detect and classify food items using AI (YOLOv8)  
- Retrieve nutritional information from structured databases  
- Receive personalized dietary recommendations based on health profile  
- Interact with an AI chatbot for nutrition guidance  

The system aims to promote **healthy long-term habits** and improve **chronic disease management** using AI.

---

# 🎯 Key Features

## 🧠 AI Food Recognition
- YOLOv8 object detection model  
- Trained on UECFOOD-100 + Egyptian food dataset  
- Detects multiple food items in real time  

## 📊 Nutritional Analysis Engine
- Calories, macronutrients, sugar, glycemic index, allergens  
- Data from USDA FoodData Central + WHO guidelines  

## 👤 Personalized Health Profiles
- Age, weight, height  
- Chronic conditions (diabetes, hypertension, etc.)  
- Allergies and dietary preferences  

## 🤖 AI Chatbot (Gemini API)
- Dietary advice  
- Meal alternatives  
- Nutrition explanations  
- Real-time assistance  

## 📚 Educational Module
- Nutrition articles  
- Infographics  
- Embedded videos  

## 🔐 Security System
- Firebase Authentication  
- Encrypted health data  
- GDPR-compliant privacy handling  

---

# 🧱 System Architecture

- **Frontend:** Flutter (Android & iOS)  
- **Backend:** Firebase (Auth, Firestore, Storage)  
- **AI/ML:** Python, YOLOv8, OpenCV  
- **Chatbot:** Gemini API  
- **Database:** USDA FoodData Central + custom dataset  

---

# 🧠 AI & Machine Learning Pipeline

## 📂 Dataset
- UECFOOD-100 (11,561 images)  
- + 9 Egyptian food classes:
  - Koshary, Molokhia, Konafa, Fool, Taameya, etc.  

## ⚙️ Preprocessing
- Resize images to 640×640  
- Bounding box annotation  
- Train/Validation/Test split (70/20/10)  

## 🤖 Model
- YOLOv8m (Ultralytics)  
- CSPDarknet backbone  
- PANet feature aggregation  
- IoU-based optimization  

---

# 🏗️ System Modules

## 1. User Authentication & Profile Management
- Firebase Authentication  
- Secure health profile storage  

## 2. Meal Capture & Analysis
- Camera or image upload  
- YOLO food detection  
- Nutritional estimation  

## 3. Recommendation Engine
- BMI-based calculations  
- Disease-specific rules  
- Personalized suggestions  

## 4. Chatbot System
- Context-aware AI assistant  
- Uses user profile + history  

## 5. Educational Content Module
- Health awareness content  
- Diet guidance materials  

---

# ⚙️ Tech Stack

| Layer        | Technology |
|--------------|------------|
| Mobile App   | Flutter |
| Backend      | Firebase |
| AI Model     | YOLOv8, OpenCV |
| Chatbot      | Gemini API |
| Database     | Firestore, USDA API |
| Version Ctrl | Git & GitHub |

---

# 🚧 Challenges

- Food recognition under different lighting conditions  
- Accurate portion estimation  
- Egyptian + regional food dataset creation  
- Real-time processing on mobile devices  
- Secure handling of medical data  
- Personalization for diverse users  

---

# 📊 System Workflow

1. User registers and creates health profile  
2. User captures meal image  
3. YOLO detects food items  
4. Nutritional database returns values  
5. Recommendation engine generates diet plan  
6. Chatbot provides assistance  
7. Educational content is shown  

---

# 📦 Deployment

- Firebase backend services  
- Android APK testing version  
- Planned Google Play Store release  

---

# 🔐 Security & Privacy

- End-to-end encrypted data  
- Firebase security rules  
- User consent management  
- GDPR-compliant data handling  
- Anonymous analytics support  

---

# 📈 Future Improvements

- Expand regional food dataset  
- Add Arabic + English multilingual support  
- Wearable device integration  
- Clinical validation with hospitals  
- Improve inference speed  

---

# 👨‍💻 Team

- Ahmed Badr Zaghloup  
- Mohammed Sayed Abdalla  
- Yousef Ahmed Mohammed  
- Mohammed Khaled Abdalla  
- Basmalla Ahmed Abdalla  
- Alaa Eid Mohammed  

**Supervisor:** Dr. Maryam Hazman  

---

# 📚 References

- YOLOv8 (Ultralytics)  
- USDA FoodData Central  
- WHO Guidelines  
- IDF Reports  
- Firebase Documentation  

---

# ⭐ Impact

FoodLens contributes to:

- AI-driven healthcare transformation  
- Nutrition awareness improvement  
- Chronic disease dietary support  
- Region-specific food intelligence  

---
## 📸 Screenshots

<!-- Add the actual image links after uploading them to your repo -->

### Onboarding Screens

![Onboarding Screen](assets/readme/onboarding.png)

### Authentication Screens

![Authentication Screens](assets/readme/auth.png)

### Main App Features

![Main Features Screens](assets/readme/home.png)

---

### Watch the video

[![Watch the video](https://i.ytimg.com/vi/2QXLybBqTmw/oardefault.jpg?sqp=-oaymwEoCJUDENAFSFqQAgHyq4qpAxcIARUAAIhC2AEB4gEKCBgQAhgGOAFAAQ==&rs=AOn4CLAWCFgzh3McINWf_d7kKGSMIo93HQ)](https://www.youtube.com/watch?v=2QXLybBqTmw&ab_channel=YousefAbdelSamad)

# 📌 License

This project was developed as a **graduation project under academic supervision**.  
For educational use only.
