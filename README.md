

## **🖱️ AirPointer - Wireless pointer control.**  

🚀 **AirPointer** turns your smartphone into a **wireless touchpad** for your Windows PC using WiFi! Move the cursor, click, scroll, and even perform gestures just like a laptop trackpad.  

---

## **✨ Features**  
✔ **Move Cursor** → Drag your finger to move the mouse.  
✔ **Left Click** → Single tap on the screen.  
✔ **Right Click** → Two-finger tap.  
✔ **Double Click** → Double tap.  
✔ **Scrolling** → Two-finger swipe up/down.  
✔ **Drag & Drop** → Tap and hold, then move.  
✔ **Middle Click** → Three-finger tap.  
✔ **Pinch Zoom** → Zoom in/out using two fingers.  

---

## **📁 Project Structure**  

```
AirPointer/
│── mobile-app/                  # React Native App (Frontend)
│   ├── src/
│   │   ├── components/
│   │   │   ├── Touchpad.js       # Touchpad Component
│   │   ├── App.js                # Main Entry
│   │   ├── config.js             # Server Configuration
│   ├── package.json
│
│── pc-server/                    # Node.js Server (Backend)
│   ├── server.js
│   ├── package.json
│
└── README.md                      # Documentation
```

---

## **🔧 Installation & Setup**  

### **1️⃣ Set Up the PC Server**  
📌 **Prerequisites:** Install **Node.js** on your PC.  

```bash
# Clone the repository
git clone https://github.com/mrajkishor/AirPointer.git
cd AirPointer/pc-server

# Install dependencies
npm install

# Start the server
node server.js
```

💡 **Your server will start on** `http://<your-pc-ip>:3000`

---

### **2️⃣ Set Up the React Native Mobile App**  
📌 **Prerequisites:** Install **React Native CLI** and set up your Android/iOS environment.  

```bash
# Navigate to mobile app folder
cd AirPointer/mobile-app

# Install dependencies
npm install

# Replace the PC's IP address in config.js
nano src/config.js  # or use any editor
```
🔧 **Edit `config.js` file**  
Replace `YOUR_PC_IP` with your local machine’s IP.  
```js
export const SERVER_IP = "YOUR_PC_IP"; // Example: "192.168.1.100"
```

```bash
# Run on Android
npx react-native run-android
```

📌 **Ensure your phone and PC are on the same WiFi network!**  

---

## **🚀 How to Use**
1. **Start the Node.js server** on your PC.  
2. **Open the AirPointer app** on your phone.  
3. **Move your finger on the screen** to control your PC mouse!  

---

## **🔧 Supported Gestures**
| Gesture | Action |
|---------|--------|
| **Single Tap** | Left Click |
| **Two-Finger Tap** | Right Click |
| **Double Tap** | Double Click |
| **Two-Finger Swipe Up/Down** | Scroll Up/Down |
| **Tap & Hold, Then Move** | Drag & Drop |
| **Three-Finger Tap** | Middle Click |
| **Pinch Zoom** | Zoom In/Out |

---

## **📌 Future Enhancements**
✅ **Bluetooth Support** (for offline usage)  
✅ **Customizable Sensitivity Settings**  
✅ **Gesture-based PC Shortcuts** (e.g., Alt+Tab)  
✅ **Multi-PC Support**  

--- 

## **🤝 Contributing**
Want to improve **AirPointer**? Feel free to fork this repo, submit issues, or create pull requests.  

```bash
# Fork the repository
git clone https://github.com/mrajkishor/AirPointer.git
```

---

## **📜 License**
🔓 This project is **open-source** under the **MIT License**.

---

## **📞 Contact & Support**
📧 **Email**: mrajkishor331@example.com  

_🔥 Like this project? Give it a **⭐ Star** on GitHub!_  
