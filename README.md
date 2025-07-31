# Yolov8 Food Classification & Recipe Recommendation

## ❗ Problem Statement

Most current food image analysis tools focus on **dish-level recognition** — they can identify a dish as *"pizza"*, but fail to detect *"pepperoni, mushrooms, and olives"*. This lack of detailed ingredient-level information limits practical cooking applications.

At the same time, existing recipe recommendation systems are **disconnected from visual input**, requiring users to **manually input** ingredients. This disconnect introduces friction in:

- Meal planning  
- Ingredient utilization  
- Culinary exploration

## 📌 Aim of the Project

This project aims to develop a two-stage intelligent system that transforms the way users interact with recipes and meal planning.

## 📊 Dataset

**FOOD INGREDIENTS DETECTION Dataset**

- **Size**:  
  - 🖼️ 1,425 training images  
  - 🧪 286 validation images  
  - 🧾 190 test images

- **Format**:  
  - All data is **image-based**  
  - Labels are provided in **YOLO format**, where each label includes:
    - `class ID`
    - `normalized bounding box coordinates` (x_center, y_center, width, height)

- **Distribution**:  
  - The dataset is **slightly imbalanced**

- **Top 5 Most Common Ingredients**:
  - 🥚 **Egg** – 203 instances  
  - 🍋 **Lemon** – 178 instances  
  - 🥒 **Cucumber** – 164 instances  
  - 🧅 **Onion** – 160 instances  
  - 🍅 **Tomato** – 150 instances

## 📦 Features

- Ingredient-level recognition from images  
- Real-time or batch recipe suggestion  
- Scalable and modular pipeline  
- Potential for integration with existing meal planner apps

## 2 Stage Pipeline

### 🔍 Stage 1: Accurate Ingredient Detection  
Leverage Yolov8 to accurately identify multiple individual ingredients present in food images.

### 📖 Stage 2: Contextual Recipe Recommendation  
Utilize the detected ingredients to retrieve contextually relevant and accessible recipes from comprehensive recipe databases using TF-IDF + T5 for recipe recommendation

## HyperParameter Tuning - Made use of Optuna for Bayesian Optimization
