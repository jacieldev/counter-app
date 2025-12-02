# Counter App

A simple React Native counter application built with Expo and TypeScript.

## Features

- 🔢 Increment counter with +1 button
- 🔄 Reset counter to zero
- 📱 Clean and minimal UI
- 🎯 FAB (Floating Action Button) components

## Tech Stack

- React Native 0.81.5
- Expo SDK ~54.0.25
- TypeScript 5.9.2
- React 19.1.0

## Installation

1. Clone the repository:
```bash
git clone https://github.com/jacieldev/counter-app.git
cd counter-app
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

## Running the App

Start the Expo development server:

```bash
npm start
# or
yarn start
```

Then choose your platform:

- Press `a` for Android
- Press `i` for iOS
- Press `w` for web

Or use platform-specific commands:

```bash
npm run android  # Run on Android
npm run ios      # Run on iOS
npm run web      # Run on web

# or with yarn
yarn android     # Run on Android
yarn ios         # Run on iOS
yarn web         # Run on web
```

## Project Structure

```
counter-app/
├── assets/          # Images and static assets
├── components/      # React components
│   └── FAB.tsx     # Floating Action Button component
├── App.tsx         # Main application component
├── app.json        # Expo configuration
├── index.ts        # Entry point
├── package.json    # Dependencies
└── tsconfig.json   # TypeScript configuration
```

## Usage

- **Increment**: Tap the "+1" button on the right to increase the counter
- **Long Press**: Hold the "+1" button to reset the counter to zero
- **Reset**: Tap the "Reset" button on the left to reset the counter to zero

