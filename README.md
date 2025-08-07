# [DropAt](https://apps.apple.com/app/dropat/id6749478138)

**DropAt** is a location-based social messaging iOS app where users can leave geotagged messages—called "drops"—at real-world locations. Others can view nearby drops on a map, but must physically visit the original location to unlock and read the full message.

This project was fully conceptualized, designed, developed, and deployed to the App Store as a solo developer effort. It is not open-source and is shared here solely for portfolio and demonstration purposes.

---

## 📱 Key Features

- **Sign in with Apple and Google** using Firebase Authentication  
- **Drop messages** at real-world locations with unique usernames  
- **Unlock drops** only when physically present at the drop location (used geoHashing)
- **Map view** of nearby drops using MapKit  
- **Report system** for inappropriate drops with manual moderation and strike-based account suspension  
- **Real-time sync** of data using Cloud Firestore

---

## 🧱 Tech Stack

- **Language & UI:** Swift, SwiftUI  
- **Architecture:** MVVM  
- **Maps & Location:** MapKit, CoreLocation  
- **Authentication & Backend:** Firebase Authentication (Apple & Google), Firestore  
- **Deployment Tools:** Xcode, TestFlight, App Store Connect  

---

## 📦 Project Architecture

Built using the **MVVM architecture** to ensure clean separation of logic, maintainability, and scalability.

---

## 🚀 Deployment

DropAt is live on the **App Store** as of 2025. you can Download the app by visiting this link :  
Includes:

- Full TestFlight testing lifecycle  
- Metadata and privacy policy setup  
- App Store Connect configuration and age rating compliance  
- Custom app icon and launch screen  
- Manual moderation system via user reports

---

## 🔒 Moderation System

- Users can report inappropriate drops via a long-press context menu  
- Each report sends an email to the moderation team  
- If confirmed, the content is removed and a **strike** is recorded  
- Accounts are **disabled after 3 confirmed strikes** to maintain safety and quality

---

## 📂 About This Repository

This repository and its code are **not open-source** and are intended only for **portfolio demonstration**. Please do not reuse or redistribute.

---

## 🧠 Developed By

**Pranay Vohra**  
Solo iOS Developer  
[LinkedIn](https://www.linkedin.com/in/pranayvohra/)  

---
Copyright © 2025 Pranay Vohra

All rights reserved.

This project and its contents are the intellectual property of Pranay Vohra.

This repository is made available for **portfolio and demonstration purposes only**. You may:

- View the code and project structure
- Reference this project as part of evaluating the author's work

You may **not**:

- Copy, modify, or distribute any part of this codebase
- Use this project as a base for your own commercial or non-commercial work
- Publish or deploy any version of this app

For collaboration or licensing inquiries, please contact the author directly.

## 📝 License

This project is licensed under a **custom no-redistribution license**.

It is intended solely for portfolio and demonstration purposes.  
All rights reserved © 2025 Pranay Vohra.  
Use, copying, or distribution of the code is not permitted.

For any licensing or collaboration inquiries, please contact me directly.
