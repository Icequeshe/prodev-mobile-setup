\# Mobile Development Environment Setup



\## Objective

To set up and test the mobile development environment using the Expo Framework for React Native, enabling app testing directly on a physical device.



---



\## Prerequisites

\- Node.js LTS installed (`node -v` → v20.x.x)

\- Visual Studio Code installed

\- Operating System: Windows 10

\- Physical Device: Android



---



\## Steps Followed



\### 1. Installed Node.js and Verified Installation

```bash

node -v

npm -v



2\. Installed Expo CLI

npm install -g expo



3\. Installed Expo Go



Visited https://expo.dev/go



Installed Expo Go from Google Play Store



Created an Expo account and logged in successfully



4\. Tested Setup

npx create-expo-app my-first-app

cd my-first-app

npm start





Scanned the QR code using Expo Go



App loaded successfully on my Android phone 🎉



Challenges Faced



Initially faced a network connection error due to firewall restrictions.



Fixed by ensuring both laptop and phone were on the same Wi-Fi network.



Needed to allow Node.js through Windows Firewall for Expo to work properly.



Outcome



Expo Go successfully installed and configured. Able to run and preview React Native apps on a physical device. Environment ready for upcoming mobile development tasks.

