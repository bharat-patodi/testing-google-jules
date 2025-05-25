# 📱 My Expo App

A cross-platform mobile app built using [Expo](https://expo.dev/) and [React Native](https://reactnative.dev/), bootstrapped with TypeScript.

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v16 or later)
- [Expo CLI](https://docs.expo.dev/workflow/expo-cli/)

```bash
npm install -g expo-cli
```

---

### 🛠 Installation

```bash
git clone https://github.com/your-username/my-expo-app.git
cd my-expo-app
npm install
```

---

### 📱 Running the App

Start the Expo development server:

```bash
npx expo start
```

Then use:

- Expo Go on Android/iOS to scan the QR code
- Android Studio/iOS Simulator for emulators

---

## 🧑‍💻 Project Structure

```
my-expo-app/
├── App.tsx                # App entry point
├── assets/                # Images, fonts, etc.
├── components/            # Shared components
├── screens/               # App screens
├── navigation/            # Navigation config (if any)
├── tsconfig.json          # TypeScript config
└── app.json               # Expo config
```

---

## ⚙️ Scripts

```bash
npm run start     # Start dev server
npm run android   # Run on Android emulator/device
npm run ios       # Run on iOS simulator (Mac only)
npm run web       # Run in browser
```

---

## 📦 Tech Stack

- Expo
- React Native
- TypeScript
- React Navigation (optional)
- AsyncStorage (optional)

---

## 📄 License

[MIT](LICENSE)

---

## 📝 Notes

This project was initialized with:

```bash
npx create-expo-app my-expo-app -t expo-template-blank-typescript
```
