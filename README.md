🍽️ FoodLens – AI-Powered Dietary Management System

FoodLens is an intelligent mobile application designed to assist individuals—especially those managing chronic conditions such as diabetes and hypertension—in making informed dietary decisions.
It leverages Computer Vision, Deep Learning, and Nutritional Data Systems to analyze meals from images and provide real-time, personalized dietary recommendations.

📌 Project Overview

FoodLens bridges the gap between medical dietary guidelines and real-world eating habits by enabling users to:

Capture a photo of their meal
Automatically detect and classify food items using AI
Retrieve nutritional information from structured databases
Receive personalized dietary recommendations based on health profile
Interact with an AI chatbot for nutrition guidance

The system promotes long-term healthy habits and improves chronic disease management through accessible AI-driven insights.

🎯 Key Features
🧠 AI Food Recognition
YOLOv8 object detection model
Trained on UECFOOD-100 + Egyptian food dataset
Detects multiple food items in real time
📊 Nutritional Analysis Engine
Calories, macronutrients, sugar, glycemic index, allergens
Uses USDA FoodData Central + WHO guidelines
👤 Personalized Health Profiles
Age, weight, height
Chronic conditions (diabetes, hypertension, etc.)
Allergies and dietary preferences
🤖 AI Chatbot Assistant (Gemini API)
Dietary advice
Meal alternatives
Nutritional explanations
Real-time support
📚 Educational Module
Nutrition articles
Infographics
Embedded educational videos
🔐 Security System
Firebase Authentication
Encrypted health data storage
GDPR-aligned privacy practices
🧱 System Architecture

FoodLens follows a modular AI-driven architecture:

Frontend: Flutter (Android & iOS)
Backend: Firebase (Auth, Firestore, Storage)
AI/ML: Python, YOLOv8, OpenCV
Chatbot: Gemini API
Database: USDA FoodData Central + custom dataset
🧠 AI & Machine Learning Pipeline
📂 Dataset Preparation
UECFOOD-100 (11,561 training images)
9 Egyptian food classes:
Koshary, Molokhia, Konafa, Fool, Taameya, etc.
Preprocessing:
Resize to 640×640
Bounding box annotation
Train/Validation/Test split: 70/20/10
🤖 Model Architecture
YOLOv8m (Ultralytics)
CSPDarknet backbone
PANet feature aggregation
IoU-based optimization
🏗️ System Modules
1. User Authentication & Profile Management
Firebase Auth
Health profile creation & updates
2. Meal Capture & Analysis
Camera / image upload
YOLO detection
Nutritional estimation
3. Recommendation Engine
BMI-based logic
Disease-specific dietary rules
Personalized meal suggestions
4. Chatbot System
Context-aware assistant
Uses user profile + meal history
5. Educational Content Module
Health awareness content
Diet planning guidance
⚙️ Tech Stack
Layer	Technology
Mobile App	Flutter
Backend	Firebase
AI Model	YOLOv8, OpenCV
Chatbot	Gemini API
Database	Firestore, USDA API
Version Ctrl	Git & GitHub
🚧 Challenges Addressed
Food recognition under different lighting conditions
Accurate portion estimation from images
Building Egyptian + regional food dataset
Real-time inference optimization
Handling sensitive medical data securely
Personalization across diverse users
📊 System Workflow
User registers & creates health profile
User captures meal image
YOLO detects food items
Nutritional database retrieves values
Recommendation engine generates diet plan
Chatbot provides guidance
User accesses educational content
📦 Deployment
Firebase backend services
Android APK for testing
Planned Google Play Store release
🔐 Security & Privacy
End-to-end encrypted user data
Firebase security rules
User consent management
GDPR-compliant data handling
Data anonymization for analytics
📈 Future Improvements
Expand regional food dataset
Multilingual support (Arabic + English)
Wearable device integration
Clinical validation with hospitals
Improve real-time inference speed
👨‍💻 Team
Ahmed Badr Zaghloul
Mohammed Sayed Abdalla
Yousef Ahmed Mohammed
Mohammed Khaled Abdalla
Basmalla Ahmed Abdalla
Alaa Eid Mohammed

Supervisor: Dr. Maryam Hazman

📚 References
YOLO: You Only Look Once (Ultralytics YOLOv8)
USDA FoodData Central
WHO Guidelines
IDF Reports
Firebase Documentation
⭐ Impact

FoodLens contributes to:

Digital health transformation
AI-driven nutrition awareness
Chronic disease support systems
Regionally intelligent food recognition
📌 License

This project was developed as a graduation project under academic supervision.
For educational and research use only.
