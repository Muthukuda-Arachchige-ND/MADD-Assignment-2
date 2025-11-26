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

# Family Cook-Off – Multiplayer Cooking Quiz (tvOS)

Family Cook-Off is an interactive, turn-based tvOS trivia game where 2–4 players compete in fun food and cooking-related questions. 
Designed specifically for the Apple TV experience, the game supports large-screen UI, Siri Remote navigation, and multi-user gameplay.

---

## 🎮 Game Overview

### 👥 Multiplayer (2–4 Players)
- Players create profiles with:
  - Name
  - Avatar (SF Symbol)
  - Favourite ingredient (for fun)
- Minimum of 2 players required to start a game.

### 🧩 Quiz Gameplay
- The quiz consists of cooking-related multiple-choice questions.
- Questions are categorized into:
  - **Easy**
  - **Medium**
  - **Hard**

### 🏆 Scoring System
- Correct answer: **+10 points**
- Wrong answer: **0 points**
- Scores are displayed at the top of the screen during gameplay.

### 🔁 Turn-Based System
- Players take turns answering questions.
- After each question, control automatically passes to the next player.

### 📘 How To Play Screen
- Simple instructions on how the game works.
- Accessible from the Welcome screen.

### 🥇 Final Results
- After all rounds, the Final Results screen displays:
  - Total scores for all players
  - Winner highlight (“Master Chef”)
  - Option to play again or return home

---

## 🧱 Tech Stack & Frameworks

- **tvOS 17+**
- **SwiftUI** with `.focusable()` and focus engine interactions
- **NavigationStack**
- **ObservableObject** + environment-based state management
- **Custom models for Player, Question, GameState**

---

## 🚀 How to Run

1. Open `FamilyCookOffTV.xcodeproj` in Xcode.
2. Select **Apple TV 4K Simulator** (3rd generation recommended).
3. Press **Run**.
4. Use the simulated Siri Remote to navigate.

---


---

## 🌟 Future Improvements (Optional)

- Add sound effects (correct/wrong)
- Add animations for winning player
- Add more question categories (world cuisine, cooking tools)
- Local multiplayer with iPhones as controllers via MultipeerConnectivity
- Achievements or badges

---

## 🧑‍💻 Author
Developed as part of **SE4041 – Mobile Application Design & Development** (Part B).

