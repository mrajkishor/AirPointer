### **📂 Folder Structure for AirPointer (React Native App)**  

```
AirPointer/
│── android/                  # Native Android files
│── ios/                      # Native iOS files
│── src/                      # Main source code
│   │── assets/               # Static assets (images, icons, fonts, etc.)
│   │── components/           # Reusable UI components
│   │   │── Touchpad.tsx       # Touchpad component
│   │   │── Button.tsx         # Custom button component
│   │   └── Loader.tsx         # Loading indicator
│   │── hooks/                # Custom hooks (optional)
│   │── navigation/           # App navigation (if using React Navigation)
│   │   └── AppNavigator.ts   # Main navigator
│   │── screens/              # Screens for the app
│   │   │── HomeScreen.tsx     # Main screen with the touchpad
│   │   │── SettingsScreen.tsx # Settings page (WiFi config, gestures, etc.)
│   │   └── AboutScreen.tsx    # Info about the app
│   │── utils/                # Utility functions (helpers, constants, etc.)
│   │── services/             # API and backend communication
│   │── config/               # App configuration (e.g., API keys)
│   │── App.js                # Main entry point
│   └── index.js              # App bootstrap file
│── .gitignore                # Git ignore file
│── package.json              # Dependencies and scripts
│── babel.config.js           # Babel configuration
│── metro.config.js           # Metro bundler configuration
│── README.md                 # Project documentation
│── yarn.lock or package-lock.json  # Dependency lock file
└── node_modules/             # Installed dependencies
```

---

### **📌 Explanation of Key Folders:**
✅ **`components/`** → Reusable UI elements like buttons, loaders, etc.  
✅ **`screens/`** → Separate screens (Home, Settings, etc.)  
✅ **`services/`** → API requests, socket connections, etc.  
✅ **`utils/`** → Helper functions like gesture recognition.  
✅ **`config/`** → Any environment or app configuration.  

### **🛠 Recommended Dependencies:**
Install core dependencies:
```sh
yarn add react-native-gesture-handler react-navigation react-native-reanimated react-native-vector-icons
```

---

> This folder structure ensures **modularity, scalability, and maintainability**. 