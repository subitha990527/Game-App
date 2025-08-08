# Game App

## 📌 Description

This project is a mobile-friendly mini game demo inspired by *Mumbai Mafia*, built using **Apache Cordova** and **sencha ExtJS**.

### Implemented Features:
- **Login Screen** with background image and mock buttons (Facebook, Google, Guest Login). You can use Guest Login.
- **Dashboard** with user name, stats (XP, Coins), and navigation buttons (Fight, Map, Inventory)
- **Fight Screen (Modal)** with enemy image, action buttons (Attack, Dodge, Use Item).
- **Map Screen (Modal)** showing areas like Dharavi, Andheri, Colaba with descriptions on click
- **Inventory Screen (Modal)** listing items like Health Potion, Knife, Armor with "Use", "Sell", "Upgrade" actions
- All screens are responsive and styled with custom UI and background images

---

## 🚀 How to Run the Project

### Prerequisites:
- Node.js
- Cordova CLI
- Gradle
- Sencha ExtJS

### Steps:

1. Clone or unzip the project folder  
2. Navigate into the project directory:

   ```bash
   cd App\cordova

### Technologies Setup

###  In Sencha Part:

  - sencha generate app -modern -ext MyApp ./MyApp
  - cd MyApp
  - sencha app refresh
  - sencha app build development
  - sencha app watch
  - sencha app build production

### In Cordova Part:

  - Install Cordova CLI
      - npm install -g cordova
  - Create Cordova Project
      - cordova create MyApp
      - cd ./MyApp/
  - Add browser platform: (Run on Browser)
      - cordova platform add browser
  - Run on a Browser
      - cordova run browser

  - Add Android platform: (Run on a Device)
      - cordova platform add android
  - Build the APK:
      - cordova build android
      - Link of APK (E:\App\Cordova\MyMobileApp\MyApp\platforms\android\app\build\outputs\apk\debug\app-debug.apk)
  - Run on a device
      - cordova run android


