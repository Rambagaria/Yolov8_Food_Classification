# Yolov8 Food Classification & Recipe Recommendation
 
## 📌 Aim of the Project

This project aims to develop a two-stage intelligent system that transforms the way users interact with recipes and meal planning.

### 🔍 Stage 1: Accurate Ingredient Detection  
Leverage Yolov8 to accurately identify multiple individual ingredients present in food images.
TF-IDF + T5 for recipe recommendation

<img width="1141" height="290" alt="image" src="https://github.com/user-attachments/assets/eb9432b3-1c75-4702-8d09-8739f60b3ed2" />

### 📖 Stage 2: Contextual Recipe Recommendation  
Utilize the detected ingredients to retrieve contextually relevant and accessible recipes from comprehensive recipe databases.

## ❗ Problem Statement

Most current food image analysis tools focus on **dish-level recognition** — they can identify a dish as *"pizza"*, but fail to detect *"pepperoni, mushrooms, and olives"*. This lack of detailed ingredient-level information limits practical cooking applications.

At the same time, existing recipe recommendation systems are **disconnected from visual input**, requiring users to **manually input** ingredients. This disconnect introduces friction in:

- Meal planning  
- Ingredient utilization  
- Culinary exploration

## 🎯 Project Goals

- ✅ Train a **multi-label classifier** to detect and localize multiple ingredients from a single food image.
- ✅ Build a **recipe retrieval engine** that automatically maps the detected ingredients to relevant recipes, minimizing the need for user input.

## 📦 Features

- Ingredient-level recognition from images  
- Real-time or batch recipe suggestion  
- Scalable and modular pipeline  
- Potential for integration with existing meal planner apps
