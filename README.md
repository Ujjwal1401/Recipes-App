# Recipes App ✨
![Android-kotlin](https://img.shields.io/badge/Android-Kotlin-blue.svg) ![glide](https://img.shields.io/badge/Library-Glide-orange.svg)

## 🌟 Introduction  
Welcome to the **Recipes App**!  
This Android application is built using **Kotlin**, **XML**, **Room Database**, and **ViewBinding**.  
It helps users browse, search, and view delicious recipes with an easy and modern UI.

---
## 🚀 Features

✅ **Browse Recipes**  
Users can explore a wide range of recipes with attractive UI cards.

✅ **Search Functionality**  
Search any recipe instantly using the built-in search bar.

✅ **Category-wise Filtering**  
Recipes are organized into categories like:  
- Main Course  
- Dessert  
- Drinks  
- Salad  
…and more!

✅ **Detailed Recipe View**  
Each recipe contains:  
- Ingredients list  
- Step-by-step cooking instructions  
- Preparation time  
- High-quality images

✅ **Popular Recipes Section**  
Highlights trending or frequently viewed recipes.

✅ **Offline Support (Room Database)**  
All recipe data is stored locally using **Room**, allowing offline access.

✅ **Smooth & Modern UI**  
Designed using XML, ViewBinding, custom shapes, and animations.

✅ **Fast Image Loading (Glide)**  
Efficient image loading with caching.

✅ **Lightweight & Optimized**  
Minimal API calls, optimized layouts, and fast performance.


---

## ✅ Prerequisites  
- Android Studio (Latest version recommended)  
- Kotlin SDK  
- Minimum SDK Support: **Android 6.0+ (API 23+)**

---

## Mobile App Screenshots 📸
<p float="center">
  <img src="https://github.com/Ujjwal1401/Recipes-App/blob/280baf4d1a4ac637a4bcb0ad251080eab1129c6b/screenshots/Splash_Screen.jpeg" title="Splash Screen" height="450px" width="225px">
  <img src="https://github.com/Ujjwal1401/Recipes-App/blob/280baf4d1a4ac637a4bcb0ad251080eab1129c6b/screenshots/Homepage.jpeg" title="Home Page" height="450px" width="225px">
  <img src="https://github.com/Ujjwal1401/Recipes-App/blob/280baf4d1a4ac637a4bcb0ad251080eab1129c6b/screenshots/Search.jpeg" title="Search Page" height="450px" width="225px">
  <img src="https://github.com/Ujjwal1401/Recipes-App/blob/280baf4d1a4ac637a4bcb0ad251080eab1129c6b/screenshots/Category.jpeg" title="Prediction Page" height="450px" width="225px">
  <img src="https://github.com/Ujjwal1401/Recipes-App/blob/280baf4d1a4ac637a4bcb0ad251080eab1129c6b/screenshots/Recipe_Ingredients.jpeg" title="Chatbot-1" height="450px" width="225px">
  <img src="https://github.com/Ujjwal1401/Recipes-App/blob/280baf4d1a4ac637a4bcb0ad251080eab1129c6b/screenshots/Recipe_Steps.jpeg" title="Chatbot-2" height="450px" width="225px">
</p>

## 🧰 Tech Stack  
- **Kotlin**  
- **XML Layouts**  
- **Room Database**  
- **ViewBinding**  
- **Glide** (for loading images)

---

## 📂 Folder Structure (Short Overview)
```

📦 Recipes-App
├── 📁 app
│ ├── 📁 manifests
│ │ └── AndroidManifest.xml
│ ├── 📁 java
│ │ └── com.practice.recipesapp
│ │ ├── AppDatabase.kt
│ │ ├── CategoryActivity.kt
│ │ ├── CategoryAdapter.kt
│ │ ├── Dao.kt
│ │ ├── HomeActivity.kt
│ │ ├── MainActivity.kt
│ │ ├── PopularAdapter.kt
│ │ ├── Recipe.kt
│ │ ├── RecipeActivity.kt
│ │ ├── SearchActivity.kt
│ │ └── SearchAdapter.kt
│ │
│ ├── 📁 java (generated)
│ │ └── com.practice.recipesapp
│ │ ├── AppDatabase_Impl
│ │ ├── Dao_Impl
│ │ └── recipe.db
│ │
│ ├── 📁 assets
│ │ └── recipe.db
│ │
│ ├── 📁 res
│ │ ├── 📁 drawable
│ │ ├── 📁 font
│ │ ├── 📁 layout
│ │ │ ├── activity_category.xml
│ │ │ ├── activity_home.xml
│ │ │ ├── activity_main.xml
│ │ │ ├── activity_recipe.xml
│ │ │ ├── activity_search.xml
│ │ │ ├── category_rv.xml
│ │ │ ├── popular_rv_item.xml
│ │ │ └── search_rv.xml
│ │ ├── 📁 mipmap
│ │ ├── 📁 values
│ │ └── 📁 xml
│ │ ├── backup_rules.xml
│ │ └── data_extraction_rules.xml
│ │
│ └── 📁 Gradle Scripts
│ ├── build.gradle.kts (Project)
│ ├── build.gradle.kts (Module: app)
│ ├── gradle.properties
│ ├── gradle-wrapper.properties
│ ├── local.properties
│ └── settings.gradle.kts
```
---

## 🙌 Credits  
- UI Resources & Icons  
- Kotlin & Android Documentation  
- Open-source community  

---

## ⭐ Support  
If you like this project, **please give a star ⭐** to this repository!

