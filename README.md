# Home Service App

A mobile app concept for discovering professional home cleaning and repair services near you, built with **React Native** and **Expo**.

> 🚧 **Project status:** This is an early-stage project. Currently it includes the app shell and a polished onboarding/landing screen; the service-browsing, booking, and account features are still to be built.

## ✨ Current Features

- Onboarding/landing screen introducing the app's purpose ("Find Professional Cleaning and Repairing Service")
- Custom themed styling (rounded cards, brand color palette)
- Cross-platform foundation — runs on iOS, Android, and web via Expo

## 🛠 Tech Stack

- **React Native** 0.74
- **Expo** SDK 51
- **expo-status-bar**

## 📂 Project Structure

```
Home-Service-App/
├── App.js                          # App entry point — currently renders the Login/onboarding screen
├── App/
│   ├── Screens/
│   │   └── LoginScreen/
│   │       └── Login.jsx            # Onboarding screen with call-to-action button
│   └── Utils/
│       └── Colors.js                 # Shared color palette (PRIMARY, WHITE, BLACK)
├── assets/                          # App icons, splash screen, and images
└── app.json                         # Expo app configuration
```

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) v18+
- [Expo CLI](https://docs.expo.dev/get-started/installation/) (or just use `npx expo`)
- Expo Go app on your phone (for quick device testing), or an Android/iOS simulator

### Running the app

1. Clone the repository
   ```bash
   git clone https://github.com/ruwanyahettiarachchi/Home-Service-App.git
   cd Home-Service-App
   ```
2. Install dependencies
   ```bash
   npm install
   ```
3. Start the Expo dev server
   ```bash
   npm start
   ```
4. Scan the QR code with the Expo Go app, or run:
   ```bash
   npm run android   # Android emulator/device
   npm run ios       # iOS simulator (macOS only)
   npm run web       # Web browser
   ```

## 🗺 Suggested Next Steps

Since this is an early-stage app, here are natural next milestones if you want to keep building it out and leveling up your React Native skills:

- Add **navigation** (e.g. React Navigation) to move from the onboarding screen into the rest of the app
- Build out a **service listing screen** (categories like cleaning, plumbing, electrical, etc.)
- Add a **service provider detail / booking screen**
- Wire up **authentication** (email/password or social login)
- Connect to a backend API (or a service like Firebase) to persist bookings and provider data
- Add **state management** (Context API or Redux Toolkit) once the app has more than one connected screen

## 🧠 Key Concepts to Learn From This Project

- Setting up and running a project with **Expo**, and understanding the managed workflow
- Building UI with **React Native core components** (`View`, `Text`, `Image`, `TouchableOpacity`) and `StyleSheet`
- Structuring a mobile app's folders by **Screens** and shared **Utils** (e.g. a central color palette) for consistency
- Cross-platform considerations — the same codebase can target iOS, Android, and web

## 📄 License

This project is available for personal and educational use. Feel free to fork and adapt it for your own learning purposes.
