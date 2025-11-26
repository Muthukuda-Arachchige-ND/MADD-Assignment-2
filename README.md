# MADD-Assignment-2
# MealMind – Smart Ingredient Scanner & Recipe Generator (iOS)

MealMind is an AI-powered iOS app that helps users turn everyday ingredients into quick, simple, and personalized recipes. 
Users can scan ingredients using photos, view predicted results, explore categorized recipes, save favourites, and switch themes.

---

## ✨ Features

### 🔍 Ingredient Recognition (AI / Vision Framework)
- Users select an image from their Photo Library.
- The app uses Apple’s Vision framework (CoreML-backed) to classify the ingredient.
- Predicted ingredient is displayed instantly.

### 🍲 Auto-Generated Recipes
- Based on the predicted ingredient, users receive a list of simple recipes.
- Each recipe includes:
  - Preparation time
  - Description
  - Step-by-step instructions
  - Ingredients list

### ⏱️ Categorized by Cooking Time
Recipes are grouped into:
- **10-minute meals**
- **20-minute meals**
- **30+ minute meals**

This helps users quickly choose meals based on time.

### ❤️ Favourite Recipes
- Users can tap the favourite icon to save recipes.
- Favourite recipes are stored locally and displayed in a dedicated list.
- Users can remove recipes from favourites at any time.

### 🌙 Dark Mode Support
- The app supports a full light/dark theme toggle.
- Users can switch themes with a button.

### 🎬 Onboarding Experience
- New users are guided through introductory onboarding screens.
- Clean introduction to the app's purpose and flow.

---

## 🧱 Tech Stack & Frameworks

- **SwiftUI** for UI and layout
- **Vision Framework** for image recognition
- **NavigationStack** for modern navigation
- **Core Data (optional)** for storing favourite recipes
- **@AppStorage** for theme persistence
- **MVVM-inspired structure** for clean code

---

## 🚀 How to Run

1. Clone or download the project from GitHub.
2. Open `MealMind.xcodeproj` in Xcode.
3. Run on any iOS Simulator (iPhone 13+ recommended).
4. To test image recognition:
   - Open Safari in the simulator → download food images → save to Photos.
   - Use the “Select Food Photo” button in the app.

---

## 📱 Supported Platforms

- iOS 17+
- Xcode 15+

---

## 🌟 Future Improvements (Optional)

- Nutrition information using Nutritionix/Edamam API  
- Barcode scan support  
- Meal planning calendar  
- Grocery list generator  
- Voice-assisted cooking mode

---

## 🧑‍💻 Author
Developed as part of **SE4041 – Mobile Application Design & Development** (Part A).
