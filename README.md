# Netflix Mobile App

This is a new [**React Native**](https://reactnative.dev) project, bootstrapped using [`@react-native-community/cli`](https://github.com/react-native-community/cli).

## 📱 Overview
This is a **Netflix Clone** mobile application built using **React Native CLI** and **JavaScript**. The app allows users to sign in, sign up, browse trending movies and TV shows, view detailed information about them, search for movies, TV shows, and actors, check profile info, view search history with details, and log out.

## ✨ Features
- 🔐 **Authentication**: Sign in and Sign up with user credentials.
- 🎬 **Trending Movies & TV Shows**: Browse the latest trending content.
- 📌 **Detailed Information**: View detailed descriptions, cast, and more for each movie/TV show.
- 🔍 **Search Functionality**: Search for movies, TV shows, and actors.
- 👤 **User Profile**: View user profile details.
- 📜 **Search History**: See past searches and detailed history.
- 🚪 **Logout**: Securely log out from the app.

# Getting Started

> **Note**: Make sure you have completed the [Set Up Your Environment](https://reactnative.dev/docs/set-up-your-environment) guide before proceeding.

## Step 1: Start Metro

First, you will need to run **Metro**, the JavaScript build tool for React Native.

To start the Metro dev server, run the following command from the root of your React Native project:

```sh
# Using npm
npm start

# OR using Yarn
yarn start
```

## Step 2: Build and run your app

With Metro running, open a new terminal window/pane from the root of your React Native project, and use one of the following commands to build and run your Android or iOS app:

### Android

```sh
# Using npm
npm run android

# OR using Yarn
yarn android
```

### iOS

For iOS, remember to install CocoaPods dependencies (this only needs to be run on first clone or after updating native deps).

The first time you create a new project, run the Ruby bundler to install CocoaPods itself:

```sh
bundle install
```

Then, and every time you update your native dependencies, run:

```sh
bundle exec pod install
```

For more information, please visit [CocoaPods Getting Started guide](https://guides.cocoapods.org/using/getting-started.html).

```sh
# Using npm
npm run ios

# OR using Yarn
yarn ios
```

If everything is set up correctly, you should see your new app running in the Android Emulator, iOS Simulator, or your connected device.

This is one way to run your app — you can also build it directly from Android Studio or Xcode.

## Step 3: Modify your app

Now that you have successfully run the app, let's make changes!

Open `App.tsx` in your text editor of choice and make some changes. When you save, your app will automatically update and reflect these changes — this is powered by [Fast Refresh](https://reactnative.dev/docs/fast-refresh).

When you want to forcefully reload, for example to reset the state of your app, you can perform a full reload:

- **Android**: Press the <kbd>R</kbd> key twice or select **"Reload"** from the **Dev Menu**, accessed via <kbd>Ctrl</kbd> + <kbd>M</kbd> (Windows/Linux) or <kbd>Cmd ⌘</kbd> + <kbd>M</kbd> (macOS).
- **iOS**: Press <kbd>R</kbd> in iOS Simulator.

## Congratulations! :tada:

You've successfully run and modified your React Native App. :partying_face:

### Now what?

- If you want to add this new React Native code to an existing application, check out the [Integration guide](https://reactnative.dev/docs/integration-with-existing-apps).
- If you're curious to learn more about React Native, check out the [docs](https://reactnative.dev/docs/getting-started).

# Backend API

This mobile app is powered by a **Node.js** backend with **Express.js** and **MongoDB**.

## Backend Setup

### Prerequisites  
- **Node.js** (LTS recommended)  
- **MongoDB** (Local or Atlas)  

### Installation  
```sh
# Clone the backend repository
git clone https://github.com/your-username/netflix-backend.git
cd netflix-backend  
npm install  
```

### Create a `.env` file with:  
```env
MONGO_URI=your_mongodb_connection_string  
PORT=5000  
```

### Start the server:  
```sh
npm start  
```

## API Endpoints  

### Auth  
- **POST** `/api/v1/auth/signup` – Create account  
- **POST** `/api/v1/auth/login` – Login  
- **POST** `/api/v1/auth/logout` – Logout  

### Movies & TV Shows  
- **GET** `/api/v1/movie/trending` – Trending movies  
- **GET** `/api/v1/tv/trending` – Trending TV shows  
- **GET** `/api/v1/movie/:id/details` – Movie details  
- **GET** `/api/v1/tv/:id/details` – TV show details  
- **GET** `/api/v1/search/:type/:query` – Search movies, TV shows, or people  

## Tech Stack  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB (Mongoose)  
- **Auth:** JWT (if implemented)  
- **Frontend:** React Native  

## 📸 Screenshots
(Add screenshots of your app here)

## 📜 License
This project is **open-source** and available under the [MIT License](LICENSE).

## 🤝 Contributing
Feel free to submit issues, feature requests, or pull requests to improve the app!

---
**Developed by [Your Name]**

