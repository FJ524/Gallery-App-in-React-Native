# React Native Gallery App 📸

A React Native mobile application built with [`@react-native-community/cli`](https://github.com/react-native-community/cli).  
This app is a complete tutorial project by **Zeba Academy**, teaching how to build a beautiful and interactive **image gallery** using React Native.  

</br>

## 🚀 Getting Started

### 1. Clone the repository
```sh
git clone https://github.com/sufyanism/gallery-application-in-react-native.git
cd react-native-gallery-app
```

### 2. Install dependencies
```sh
npm install
# OR
yarn install
```

### 3. Run the app
```sh
npm run android
# OR
npm run ios
```

</br>

## ✨ Features

### 🖼 Gallery Grid & Image Preview Modal
- Displays all images in a **2-column responsive grid**.  
- Tap any image to **view it fullscreen** in a smooth modal view.

### 🔍 Search Bar & Filters
- Search images by **title or keyword**.  
- Filter by categories: **All, Nature, Urban, Other, and Favorites.**

### ❤️ Favorites Feature
- Tap the **heart icon** to add/remove favorites.  
- View only liked images by switching to the **Favorites category.**

</br>

## ⚙️ Usage

- Use the search bar at the top to filter images by title.  
- Tap category buttons to view filtered results.  
- Tap an image to open it in fullscreen.  
- Tap the heart icon to favorite/unfavorite.  
- Close fullscreen preview using the **X button.**

</br>

## 🧩 Code Overview

- **App.jsx** handles all main logic: gallery, search, filters, favorites, and modal preview.  
- Uses React Native components like `FlatList`, `Modal`, `TextInput`, and `TouchableOpacity`.  
- State is managed using **React Hooks** (`useState`, `useRef`).  
- **Animated API** is used for smooth favorite toggle effects.

</br>

## 🛠 Tech Stack

- [React Native](https://reactnative.dev)  
- JavaScript / JSX  
- React Hooks  
- React Native Animated API

</br>
