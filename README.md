🍽️ FoodLens – AI-Powered Dietary Management System

FoodLens is an intelligent mobile application designed to assist individuals—especially those managing chronic conditions such as diabetes and hypertension—in making informed dietary decisions. It leverages Computer Vision, Deep Learning, and Nutritional Data Systems to analyze meals from images and provide real-time, personalized dietary recommendations.

📌 Project Overview

Modern dietary management is often complex and difficult to maintain consistently. FoodLens bridges the gap between medical dietary guidelines and real-world eating habits by enabling users to:

Capture a photo of their meal
Automatically detect and classify food items using AI
Retrieve nutritional information from structured databases
Receive personalized dietary recommendations based on health profile
Interact with an AI chatbot for nutrition guidance

The system is designed to promote long-term healthy habits and improve chronic disease management through accessible AI-driven insights.

🎯 Key Features
🧠 AI Food Recognition
Uses YOLOv8 object detection model
Trained on UECFOOD-100 dataset + Egyptian food dataset
Detects multiple food items in real time
📊 Nutritional Analysis Engine
Extracts calories, macronutrients, sugar, glycemic index, and allergens
Uses USDA FoodData Central + WHO-based dietary guidelines
👤 Personalized Health Profiles
Stores user-specific data:
Age, weight, height
Chronic conditions (diabetes, hypertension, etc.)
Allergies and dietary preferences
🤖 AI Chatbot Assistant
Powered by Gemini API
Provides:
Dietary advice
Meal alternatives
Nutritional explanations
Real-time support
📚 Educational Module
Nutrition articles
Infographics
Embedded educational videos
🔐 Secure System
Firebase Authentication
Encrypted health data storage
GDPR-aligned privacy practices
🧱 System Architecture

FoodLens follows a modular architecture:

Frontend: Flutter (Android & iOS)
Backend: Firebase (Auth, Firestore, Storage)
AI/ML: Python, YOLOv8, OpenCV
Chatbot: Gemini API
Database: USDA FoodData Central + custom food dataset
🧠 AI & Machine Learning Pipeline
Dataset Preparation
UECFOOD-100 dataset (11,561 training images)
Extended with 9 Egyptian food classes:
Koshary, Molokhia, Konafa, Fool, Taameya, etc.
Image preprocessing:
Resizing to 640×640
Annotation using bounding boxes
Train/Validation/Test split: 70/20/10
Model
YOLOv8m (Ultralytics)
PANet feature aggregation
CSPDarknet backbone
IoU-based bounding box optimization
🏗️ System Modules
1. User Authentication & Profile Management
Firebase Auth integration
Health profile creation and updates
2. Meal Capture & Analysis
Image upload or camera input
YOLO-based detection
Nutritional estimation per detected food
3. Recommendation Engine
BMI-based calculations
Disease-specific dietary rules
Personalized meal suggestions
4. Chatbot System
Context-aware nutrition assistant
Uses user profile + meal history
5. Educational Content Module
Health awareness materials
Diet planning guidance
⚙️ Tech Stack
Layer	Technology
Mobile App	Flutter
Backend	Firebase
AI Model	YOLOv8, OpenCV
NLP Chatbot	Gemini API
Database	Firestore, USDA API
Version Control	Git & GitHub
🚧 Challenges Addressed
Food recognition under varying lighting conditions
Portion size estimation from images
Building a culturally relevant food dataset (Egyptian cuisine)
Ensuring real-time performance on mobile devices
Handling sensitive health data securely
Personalization across diverse health profiles
📊 System Workflow
User registers and creates health profile
User captures meal image
YOLO model detects food items
Nutritional database returns food composition
System generates personalized recommendation
Chatbot provides additional guidance
User accesses educational content
📦 Deployment
Firebase backend deployment
Android APK for testing
Planned Google Play Store release
🔐 Security & Privacy
End-to-end encrypted user data
Secure Firebase rules
User consent management
GDPR-compliant data handling
Data anonymization for analytics
📈 Future Improvements
Expand dataset with more regional foods
Multilingual support (Arabic + English)
Integration with wearable health devices
Clinical validation with healthcare providers
Improved real-time accuracy optimization
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
World Health Organization (WHO)
International Diabetes Federation (IDF)
Firebase Documentation
⭐ Impact

FoodLens contributes to:

Digital health transformation
AI-driven nutrition awareness
Chronic disease dietary support
Regionally relevant food intelligence systems

📌 License

This project is developed as a graduation project under academic supervision.
For research and educational use only.
